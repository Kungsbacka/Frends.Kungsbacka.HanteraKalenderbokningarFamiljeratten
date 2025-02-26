# Hantera kalenderbokningar - IF - Familjerätten

![process](https://raw.githubusercontent.com/Kungsbacka/Frends.Kungsbacka.HanteraKalenderbokningarFamiljeratten/refs/heads/main/Hantera%20kalenderbokningar%20-%20process.png)


Frends-process för att hantera bokningar och avbokningar från OpenE till kalendrar i outlook.

## Environment variables
| Namn  | Funktion |
| ------------- | ------------- |
| IFFamiljerattenCalendarId  | Sätts som process variabel #var.calendarId. Id:t pekar mot en kalender i OpenE.  |
| IFFamiljerattenCalendarGuid  | Unik identifierare för en kalender, används för att identifiera vilka bokningar i outlook som hör till respektive kalender i OpenE. Sparas på en outlook-bokning som SingleValueExtendedProperties.  |

## Använda tasks
| Namn  | Länk |
| ------------- | ------------- |
| Frends.Kungsbacka.Graph  | https://github.com/Kungsbacka/Frends.Kungsbacka.Graph  |
