# Test de charge & Observabilité : Concurrence + Verrou DB + Resilience4j + Actuator Metrics

## Ce que ce TP permet de vérifier
* Des emprunts concurrents arrivent sur 3 instances (8081/8083/8084).
* Le verrou DB empêche le stock de devenir négatif.
* Quand pricing-service tombe, book-service continue grâce au fallback.
* Les métriques Actuator confirment que Retry et CircuitBreaker se déclenchent.

## Structure 
<img width="467" height="490" alt="Capture d&#39;écran 2026-01-11 212034" src="https://github.com/user-attachments/assets/4d046c29-f7f2-4837-9093-f137df52b49f" />

## Exécution 
<img width="959" height="502" alt="Capture d&#39;écran 2026-01-11 205639" src="https://github.com/user-attachments/assets/f463ee6a-3b80-40f4-8657-3c05f7d0a194" />
<img width="699" height="499" alt="Capture d&#39;écran 2026-01-11 205703" src="https://github.com/user-attachments/assets/fc37570d-ff98-42ca-bc7f-65f17ec4e654" />
<img width="960" height="204" alt="Capture d&#39;écran 2026-01-11 205924" src="https://github.com/user-attachments/assets/b1e80442-df12-4463-b1b8-241435daed38" />
<img width="480" height="502" alt="Capture d&#39;écran 2026-01-11 211634" src="https://github.com/user-attachments/assets/373b46b1-66b9-46e2-8271-b903169f7c4f" />
<img width="960" height="185" alt="Capture d&#39;écran 2026-01-11 211009" src="https://github.com/user-attachments/assets/c901b43e-4e42-442e-9f7b-6d54a6c9f27c" />

## Auteur
* Nom : BEN-LAGHFIRI Majeda
* Cours: Architecture Microservices : Conception, Déploiement et Orchestration
* Date : Janvier 2026
* Encadré par : Pr.Mohamed LACHGAR





