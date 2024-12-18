---
title: Brief6 - Kubernetes executive summary
descriptions: View the slide with "Slide Mode".
slideOptions:
    theme: moon
    transtion: 'concave'
    backgroundTransition: 'fade'
   
<!-- .slide: data-background="https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg"
    
---


# ***Brief 6: Kubernetes executive summary***
[Github du brief 6](https://github.com/simplon-choukriraja/brief6)
[Résultat](https://brief6.simplon-raja.space/)
[Présentation](https://hackmd.io/p/HXcyMPOZSImciujCjyzh6A) 


---


# ***Kubernetes***


---


***Kubernetes (k8s)***  :  plateforme open-source qui automatise la gestion et l’orchestration des conteneurs sur un parc “cluster” de machines


---

# ***Avantages***

---

 * Orchestrez les conteneurs sur plusieurs hôtes,
 * Contrôlez et automatisez les déploiements et les mises à jour des applications,
 * Monter et ajouter du stockage,
 * Manipuler rapidement le scaling

---


# ***Azure Kubernetes Service (AKS)***

---

***Azure Kubernetes Service (AKS)*** : simplifie la gestion et le déploiement des applications basées sur les conteneurs.

---


## **Container Redis** 

---

***Remote Dictionary Server(Redis)*** :  magasin de structure de données clé/valeur en mémoire open source rapide.

---

* ***Service  --> LoadBalancer,***
* ***Service  --> ClusterIP,***
* ***Kubernetes Secret,***
* ***Stockage --> PersistentVolumeClaim*** 


---


## ***Application Vote***

---

*  ***Deployé l’application Azure Voting App***
*  ***Redis_PWD***
*  ***Service  --> LoadBalancer,***
*  ***ClusterIP***
*  ***Autoscaling à 70% de CPU***
*  ***8 instances MAX***
*  ***HorizontalPodAutoscaler***


---

## ***Application Gateway***

---

* ***Créer cluster AKS --> AGIC***
* ***4 nodes***
* ***Ingress***

---

## ***Certificat TLS***

---

* ***Créer le certificat TLS***
* ***DNS***

---

## ***Difficultés rencontrées à nouveau***

---


* ***Difficulté à comprendre certains termes***
* ***Création du certificat TLS***
* ***Difficulté à trouver comment créer des liens***

---

## ***Résultat***

---

<img width="850" alt="Résultat" src="https://user-images.githubusercontent.com/108053084/196186146-88655fe7-f535-4cfc-8e0e-b22ad1c7dc34.PNG">


---

## ***Topologie***

---

<img width="500" alt="topologie1" src="https://user-images.githubusercontent.com/108053084/196277702-dccd766e-e51c-4c33-b191-a837a8aa823e.PNG">


---

## ***Test de charge***

---

<img width="500" alt="test de charge" src="https://user-images.githubusercontent.com/108053084/196381598-f60e25aa-dca0-432e-af44-7dab0452b273.PNG">


---

# ***MERCI DE VOTRE ATTENTION*** 


---

