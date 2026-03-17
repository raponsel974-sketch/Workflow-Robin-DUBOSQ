# 03 — Process & ATS

Pipeline de recrutement et configuration ATS utilisés chez Fnac Darty (Talentsoft + ATS Excel interne).

---

## Pipeline — 6 étapes

| Étape | Description | Owner | SLA cible |
|---|---|---|---|
| Identifié | Profil sourcé, pré-qualifié téléphone | RH | J+2 |
| Entretien RH (Moi) | Validé RH, transmis N+1 | RH | J+3 |
| Entretien Manager | Entretien N+1 planifié / réalisé | Manager | J+7 |
| Tests Techniques | Cas pratique ou évaluation métier | Manager | J+10 |
| Tests PAPI | Évaluation comportementale si requis | RH | J+12 |
| Embauché | Offre acceptée, promesse signée | RH | J+15 max |

Finalités possibles : **En process · Refusé · Retiré · Stand by**

---

## Structure ATS Excel (V12)

| Onglet | Contenu |
|---|---|
| Dashboard | KPIs visuels, filtres dynamiques |
| Preferences | Recruteurs, directions, sources, statuts pipeline |
| JobOpenings | Postes ouverts (JOB ID, département, date brief, statut) |
| Candidates | Candidatures — 21 colonnes : profil, source, pipeline, notes RH, retour manager, score |
| Calc | Calculs automatiques pour le dashboard |

**Colonnes clés — onglet Candidates**

| Champ | Usage |
|---|---|
| JOB ID | Lien vers le poste |
| Sources | Canal d'origine |
| Processsus (Pipeline) | Étape courante |
| Finalité | Décision finale |
| HR VIEW | Notes recruteur |
| HIRING MANAGER VIEW | Retour N+1 |
| Note entretien | Score entretien |
| TESTS PAPI | Résultat PAPI |

---

## Sources tracées

Talentsoft · Site carrière · LinkedIn · Cooptation · Hellowork · Indeed · Chasse

---

## Règles de fonctionnement

1. **1 ligne = 1 candidature** — un même profil peut apparaître sur plusieurs postes
2. **JOB ID obligatoire** sur chaque ligne pour lier candidature et poste
3. **Pipeline mis à jour à chaque étape** — aucune candidature sans statut à jour
4. **HR VIEW obligatoire** après chaque contact candidat
5. **Finalité documentée** sur tout process terminé

---

## Filtres dashboard disponibles

Recruteur · Département · Source · Statut poste · Décision finale · Statut pipeline · Mois / Année / Plage de dates
