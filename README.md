# normes-robuste-de-dev-appweb-prompt

Applique le Principes SOLID & KISS : Le code doit être modulaire, hautement découplé et simple à lire. 
- Sécurité par défaut (OWASP) : Implémente systématiquement la validation des entrées (input sanitization), la protection contre les injections SQL, XSS, et CSRF. 
- Gestion des erreurs : Tout code asynchrone ou à risque doit être enveloppé dans des blocs de capture d'erreur (try/catch) avec des logs explicites (sans exposer de données sensibles). 
- Performance et Scalabilité : Optimise les requêtes (évite le problème N+1) et propose l'utilisation de caches ou de files d'attente si nécessaire.
