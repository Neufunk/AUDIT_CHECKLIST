CHECKLIST AUDIT 

# LAN
1. Validation schéma réseau-redondance
- [ ] PASS
- [ ] FAIL
- [ ] N.A.
2. Vérification des dates-time des devices (serveur NTP en place)
3. Centralisation et conservation des logs
4. Vérification des mots de passes des devices (mot de passe par défaut)
5. Vérification accès SNMP avec communauté par défaut (Public-private)
6. Ségrégation des réseaux
7. WIFI
8. Réseau Guest
 
# SERVEURS / MACHINES
1. Vérification des domain admins
2. Vérification antivirus
        2.1 Présence sur toutes les machines
        2.2 Tampering protection
        2.3 Eicar
        2.4 Licence
3. Vérification si machines à jours
4. Vérification du process de mise à jour
5. Configuration des droits sur les shares (Par groupe et non par utilisateurs)
6. Applocker
7. GPO en place
8. LAPS
9. Admin locaux
10. Backups (copie distante- configuration - virtual standby)
11. Virtualisation (vérification des redondances, config sécurtié, reboot auto, ssh coupé)
12. Exchange: (Quarantaine, certificat, séparation des disques )
 
 
# WAN
1. Ports ouverts
2. Services exposés
3. Web filtering
4. Filtrage des ports en sortie
5. Licences FW
6. Antivirus
7. Connexions VPN (MFA, certificat, limite connexion concurrentes, etc)
 
# Mail
1. Vérification antispam
2. SPF
3. DKIM - Signature mail sortants
4. DMARC - Que faire si DKIM et SPF ne sont pas valide
