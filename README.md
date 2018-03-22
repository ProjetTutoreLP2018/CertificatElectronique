# CertificatElectronique
Permet de générer un certificat associé à une clé privée : 
- la méthode GenerateCACertificate() permet de générer une clé privée, il suffit de passer à la méthode le Common Name (CN) correspondant à un nom de domaine 
- la méthode GenerateSelfSignedCertificate() permet de générer un certificat auto-signé en fonction des paramètres passés à la méthode : deux CN et la clé privée
