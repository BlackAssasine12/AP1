# Libraries und Frameworks

## Einführung
In der Softwareentwicklung spielen **Libraries (Bibliotheken)** und **Frameworks** eine zentrale Rolle.  
Beide bieten wiederverwendbare Bausteine, um Entwicklungsprozesse effizienter und strukturierter zu gestalten. Dennoch gibt es deutliche Unterschiede in ihrer Funktionsweise und im Einfluss auf den Programmierstil.

---

## Was ist eine Library?
- **Definition**: Eine Library ist eine Sammlung von Funktionen, Klassen oder Modulen, die in Programmen genutzt werden können.  
- **Merkmal**: Der Entwickler behält die Kontrolle über den Programmablauf und ruft gezielt Funktionen aus der Library auf.  
- **Beispiele**:  
  - NumPy (Python) → mathematische Funktionen  
  - React-DOM (JavaScript) → DOM-Operationen  
  - jQuery (JavaScript) → Vereinfachung von DOM-Manipulation  
  - Newtonsoft.Json (C#) → JSON-Serialisierung  

---

## Was ist ein Framework?
- **Definition**: Ein Framework ist ein umfassendes Grundgerüst für Anwendungen. Es definiert die Struktur und oft auch den Ablauf des Programms.  
- **Merkmal**: Der Entwickler integriert seine Logik in die vom Framework vorgegebenen Strukturen. Man spricht vom **„Inversion of Control“ (IoC)** – das Framework ruft den Code des Entwicklers auf.  
- **Beispiele**:  
  - Angular (JavaScript)  
  - Django (Python)  
  - Spring (Java, Enterprise-Entwicklung)  
  - ASP.NET MVC (C#)  

---

## Unterschiede zwischen Libraries und Frameworks

| Merkmal              | Library                                          | Framework                                              |
|----------------------|--------------------------------------------------|--------------------------------------------------------|
| **Kontrolle**        | Entwickler steuert den Ablauf selbst             | Framework bestimmt den Ablauf (Inversion of Control)   |
| **Flexibilität**     | Hohe Flexibilität, einzelne Funktionen nutzbar   | Geringere Flexibilität, da Struktur vorgegeben ist     |
| **Einstieg**         | Leichter Einstieg, da selektive Nutzung möglich  | Höherer Lernaufwand durch Regeln & Vorgaben            |
| **Beispiele**        | NumPy, Lodash, jQuery, Newtonsoft.Json           | Angular, Django, Spring, ASP.NET MVC                   |

---

## Vorteile & Nachteile

### Libraries
**Vorteile**
- Flexibel und vielseitig einsetzbar  
- Einfacher Einstieg  
- Leicht in bestehende Projekte integrierbar  

**Nachteile**
- Entwickler muss die Gesamtstruktur selbst entwerfen  
- Gefahr von unübersichtlichem Code bei vielen Libraries  

---

### Frameworks
**Vorteile**
- Klare Struktur und Vorgaben → konsistenter Code  
- Viele Funktionen sind bereits integriert (z. B. Datenbankanbindung, Routing)  
- Gut geeignet für große Projekte und Teams  

**Nachteile**
- Steile Lernkurve  
- Weniger flexibel → Entwickler ist an das Framework gebunden  
- Abhängigkeit vom Framework (Updates, Community, Support)  

---

## Praxisbeispiele

### JavaScript

#### Library (React)
```javascript
import React from 'react';
import ReactDOM from 'react-dom';

function HelloWorld() {
  return <h1>Hello, World!</h1>;
}

// Entwickler ruft die Library selbst auf
ReactDOM.render(<HelloWorld />, document.getElementById('root'));
```
👉 Der Entwickler entscheidet **wann und wie** die Library genutzt wird.

#### Framework (Angular)
```typescript
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  template: `<h1>{{ title }}</h1>`
})
export class AppComponent {
  title = 'Hello, World!';
}
```
👉 Angular gibt eine feste **Struktur** vor (Komponenten, Module, Templates). Das Framework ruft den Code des Entwicklers automatisch auf.

---

### C# (OOP)

#### Library (Newtonsoft.Json)
```csharp
using System;
using Newtonsoft.Json;

public class Person {
    public string Name { get; set; }
    public int Age { get; set; }
}

class Program {
    static void Main() {
        var person = new Person { Name = "Anna", Age = 25 };

        // Entwickler entscheidet, wann die Library genutzt wird
        string json = JsonConvert.SerializeObject(person);
        Console.WriteLine(json);
    }
}
```
👉 Newtonsoft.Json ist eine Library, die gezielt aufgerufen wird – die Kontrolle bleibt beim Entwickler.

#### Framework (ASP.NET MVC)
```csharp
using Microsoft.AspNetCore.Mvc;

public class HomeController : Controller {
    public IActionResult Index() {
        return View();
    }
}
```
👉 ASP.NET MVC gibt vor, dass eine Controller-Klasse Methoden wie `Index()` bereitstellt.  
Das **Framework** kümmert sich um den Aufruf, Routing und Ablauf – der Entwickler schreibt nur die Logik.

---

## Wann sollte man Libraries nutzen?
- Bei **kleinen Projekten** oder wenn nur bestimmte Funktionen benötigt werden  
- Wenn man **volle Kontrolle** über den Ablauf behalten möchte  
- Wenn man bestehende Projekte nur erweitern möchte  

---

## Wann sollte man Frameworks nutzen?
- Bei **größeren Projekten**, die eine einheitliche Struktur benötigen  
- Wenn mehrere Entwickler im Team arbeiten und klare Vorgaben wichtig sind  
- Wenn viele Standardfunktionen (Routing, Sicherheit, Datenbankzugriff) bereits integriert sein sollen  

---

## Zusammenfassung
- **Library**: Werkzeugkasten – man nimmt, was man braucht, behält aber die Kontrolle.  
- **Framework**: Vorgegebenes Grundgerüst – man arbeitet innerhalb der vorgegebenen Struktur.  
- **Entscheidung**: Hängt von Projektgröße, Teamgröße, Flexibilitätsbedarf und Zeitrahmen ab.  
