**VERSION : 1.0**

**Authors**  
Rodrigo Parodi

**REVISION HISTORY**

| Version    | Date        | Authors      | Notes        |
| ----------- | ----------- | ----------- | ----------- |
| 1.0 | 27/06/2024 | Rodrigo Parodi| creazione struttura|

# Table of Contents

1. [Introduction](#p1)
	1. [Document Scope](#sp1.1)
	2. [Definitios and Acronym](#sp1.2) 
	3. [References](#sp1.3)
2. [System Description](#p2)
	1. [Context and Motivation](#sp2.1)
	2. [Project Objectives](#sp2.2)
3. [Requirement](#p3)
 	1. [Stakeholders](#sp3.1)
 	2. [Functional Requirements](#sp3.2)

  
  

<a name="p1"></a>

## 1. Introduction

<a name="sp1.1"></a>

### 1.1 Document Scope


<a name="sp1.2"></a>

### 1.2 Definitios and Acronym


| Acronym				| Definition | 
| ------------------------------------- | ----------- | 
| ISBN                                 | INterntiona lstandar book Number |

<a name="sp1.3"></a>

### 1.3 References 

<a name="p2"></a>

## 2. System Description
<a name="sp2.15"></a>
>>Il sistema dovrà permettere di memorizzare info 
### 2.1 Context and Motivation

<a name="sp2.2"></a>
Progettazione software per gestone privata libri(titolp, autore, anno e ISBN), 
deve inoltre recuperare info su un libro e add e remove libri da libreria)


### 2.2 Project Obectives 

<a name="p3"></a>

## 3. Requirements

| Priorità | Significato | 
| --------------- | ----------- | 
| M | **Mandatory:**   |
| D | **Desiderable:** |
| O | **Optional:**    |
| E | **future Enhancement:** |

<a name="sp3.1"></a>
### 3.1 Stakeholders
1. Utente generico: ha come obiettivo memorizzare tutti i libri che vuole in un unico posto.
2.  

<a name="sp3.2"></a>
### 3.2 Functional Requirements 

<a name="sp3.2"></a>
![Use Case Diagram](IMG/usecase.png)

#### 3.2.1 Aggiungi Libro
<b>NOME</b> Aggiungi Libro

<b>Precondizione</b> 

<b>Priorità</b> Mandatory

<b>Stakeholder principale </b> Utente

<b>Scenario Principale</b>

	1. Sistema chiede di inserire un nuovo titolo

 	2. Utente isnerisce titolo

  	3. Sistema chiede di inserire autore  
   	4. Utente inserise autore
    
    	5. Sistema chiede di inserire  anno di pubblicazione

     	6. Utente inserisce un anno
      	7. Sistema chiede di inserire ISBN
        8. Utnete inserisce ISBN
	9. Il sistema valida il nuovo libro corettamente
       10. Il sistema inserisce libro in libreria
       11. Sistema saluta 

<b>Scenario Alternativvo</b>
   2A. Utente inserisce titolo non valido
   1. Sistema notifica titolo non vlaido
   2. Sistema torna a punto 1 di scenario principaleù
      
<b>Scenario Alternativo</b>
  9A. Esiste già un libro con quell'ISBN

   1. Sistema notifica l'utente
   2. Sistema mostrea il libro con stesso ISBN
   3. Sistema chiede se vuole sostituire il vecchio libro
   4. utente dice si
   5. Sistema cancella libr
   6. Sistem inserisce nuovo libro

<b>Scenario Alternativvo</b>
9A.4A Utente dice di no
   1.Sistema chiede di modificare ISBN
   2.Utente dice si
   3.Sistema torna a putno 8 di scenario principale
   
<b>Post-condizoni</b>


<a name="sp3.2"></a>
#### 3.2.2 Deposito
<b>NOME</b>

<b>Precondizione</b>

<b>Priorità</b>

<b>Stakeholder</b>

<b>Scenario Principale</b>

<b>Scenario Alternativvo</b>

<b>Post-condizoni</b>

<a name="sp3.2"></a>
#### 3.2.3 Trasferimento
<b>NOME</b>

<b>Precondizione</b>

<b>Priorità</b>

<b>Stakeholder</b>

<b>Scenario Principale</b>

<b>Scenario Alternativvo</b>

<b>Post-condizoni</b>

<a name="sp3.2"></a>
#### 3.2.4 Saldo
<b>NOME</b>

<b>Precondizione</b>

<b>Priorità</b>

<b>Stakeholder</b>

<b>Scenario Principale</b>

<b>Scenario Alternativvo</b>

<b>Post-condizoni</b>

<a name="sp3.2"></a>
#### 3.2.5 Accensione
<b>NOME</b>

<b>Precondizione</b>

<b>Priorità</b>

<b>Stakeholder</b>

<b>Scenario Principale</b>

<b>Scenario Alternativvo</b>

<b>Post-condizoni</b>


<a name="sp3.2"></a>
#### 3.2.5 Spegnimento
<b>NOME</b>

<b>Precondizione</b>

<b>Priorità</b>

<b>Stakeholder</b>

<b>Scenario Principale</b>

<b>Scenario Alternativvo</b>

<b>Post-condizoni</b>

