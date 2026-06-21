# Drielaagse webarchitecturen en MVC-architecturen met Struts, Spring en Java

🔗 **Bijbehorend document:**
[Drielaagse architecturen en MVC-architecturen met Struts, Spring en Java](https://stahe.github.io/nl-java-web3tier-mars-2005/)

---

## 📘 Inleiding

Deze repository bevat de inhoud van twee artikelen die tussen maart en juli 2005 op Developpez.com zijn gepubliceerd.
Ze behandelen Java-webarchitecturen vanuit een pedagogische en stapsgewijze benadering:

1. **Spring IoC**
   Inleiding tot **Inversion of Control (IoC)**, ook wel **Dependency Injection (DI)** genoemd, aan de hand van het Spring-framework.

2. **Drie voorbeelden van drielaagse webarchitecturen**
   Presentatie van een vereenvoudigde webapplicatie voor het beheer van online aankopen, geïmplementeerd volgens een **MVC (Model–View–Controller)**-architectuur en uitgewerkt in drie technische varianten.

---

## 🏗️ Behandelde architecturen

De voorbeeldapplicatie is gestructureerd volgens een **drielaagse** architectuur:

* **Weergavelaag (View)**
* **Bedrijfslogica (Business Logic)**
* **Gegevenslaag (Data Access)**

Het **MVC**-model is op drie verschillende manieren geïmplementeerd:

### 1️⃣ Servlet + JSP

* Een **controller-servlet**
* **JSP-pagina’s** voor de weergaven
* Handmatige MVC-architectuur

### 2️⃣ Struts

* MVC-implementatie op basis van het **Struts**-framework
* Centralisatie van de besturing via `ActionServlet`
* Declaratieve mapping van acties

### 3️⃣ Spring MVC

* Gebruik van het **Spring MVC**-framework
* Integratie met de IoC-container van Spring
* Configuratie gericht op afhankelijkheidsinjectie

---

## 🎯 Leerdoelen

* Het principe van **drielaagse architectuur** begrijpen
* Het **MVC-model in een Java-webomgeving** beheersen
* Kennismaken met **Inversion of Control (IoC)** en afhankelijkheidsinjectie
* Verschillende benaderingen van MVC-implementatie vergelijken
* De voordelen van frameworks ten opzichte van een handmatige implementatie begrijpen

---

## 🧩 Gebruikte technologieën

* Java
* Servlets
* JSP
* Struts
* Spring Framework
* Spring MVC

---

## 📚 Doelgroep

Dit materiaal is bedoeld voor:

* Java-ontwikkelaars die inzicht willen krijgen in klassieke webarchitecturen
* Iedereen die “handmatige” MVC wil vergelijken met MVC via een framework

---

## 🏷️ Historische context

Deze artikelen dateren uit 2005 en weerspiegelen de stand van zaken op het gebied van Java-webontwikkeling in die tijd.

