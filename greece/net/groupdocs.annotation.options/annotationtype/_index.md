---
title: AnnotationType
second_title: GroupDocs.Σχολιασμός για Αναφορά API .NET
description: Απαρίθμηση που περιγράφει τύπους σχολιασμών που υποστηρίζονται από GroupDocs.Σχολιασμός για .NET
type: docs
weight: 960
url: /el/net/groupdocs.annotation.options/annotationtype/
---
## AnnotationType enumeration

Απαρίθμηση που περιγράφει τύπους σχολιασμών που υποστηρίζονται από GroupDocs.Σχολιασμός για .NET

```csharp
[Flags]
public enum AnnotationType
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| None | `0` | Προεπιλεγμένη τιμή |
| Area | `2` | Ο τύπος σχολιασμού περιοχής που επισημαίνει την ορθογώνια περιοχή εντός της σελίδας εγγράφου |
| Arrow | `4` | Ο τύπος σχολιασμού που σχεδιάζει ένα βέλος στη σελίδα του εγγράφου |
| Distance | `8` | Ο τύπος σχολιασμού που μετρά την απόσταση μεταξύ των στοιχείων μιας σελίδας εγγράφου |
| Ellipse | `10` | Ο σχολιασμός της ελλειπτικής μορφής που επισημαίνει μέρη του περιεχομένου του εγγράφου |
| Link | `20` | Ο τύπος σχολιασμού που αντιπροσωπεύει μια υπερσύνδεση σε έναν απομακρυσμένο πόρο |
| Point | `40` | Ο τύπος σχολιασμού σημείου που κολλά ένα σχόλιο σε οποιοδήποτε μέρος εντός του εγγράφου page |
| Polyline | `80` | Ο τύπος σχολιασμού πολυγραμμής που επιτρέπει την προσθήκη σχημάτων σχεδίασης και γραμμών ελεύθερου σε μια σελίδα εγγράφου |
| ResourcesRedaction | `100` | Ο τύπος σχολιασμού που κρύβει το περιεχόμενο κειμένου πίσω από το μαύρο ορθογώνιο |
| TextField | `200` | Ο τύπος σχολιασμού πεδίου κειμένου αντιπροσωπεύει κειμενικό σχόλιο μέσα σε έγχρωμο πλαίσιο |
| TextHighlight | `400` | Ο τύπος σχολιασμού που επισημαίνει και σχολιάζει επιλεγμένο κείμενο |
| TextRedaction | `800` | Ο τύπος σχολιασμού που γεμίζει μέρος του επιλεγμένου κειμένου με μαύρο ορθογώνιο. |
| TextReplacement | `1000` | Ο τύπος σχολιασμού που αντικαθιστά το αρχικό κείμενο με άλλο παρεχόμενο τμήμα κειμένου |
| TextStrikeout | `2000` | Ο τύπος σχολιασμού που επισημαίνει το τμήμα κειμένου με μια διαγραφή styling |
| TextUnderline | `4000` | Ο τύπος σχολιασμού που επισημαίνει κείμενο με υπογράμμιση στυλ |
| Watermark | `8000` | Ο τύπος σχολιασμού που προσθέτει υδατογράφημα κειμένου στη σελίδα εγγράφου |
| Image | `10000` | Ο τύπος σχολιασμού που προσθέτει επικάλυψη εικόνας στο περιεχόμενο της σελίδας εγγράφου |
| Dropdown | `20000` | Ο τύπος στοιχείου που προσθέτει αναπτυσσόμενο στοιχείο για έγγραφο pdf**μόνο** |
| Checkbox | `21000` | Ο τύπος σχολιασμού που προσθέτει το πλαίσιο ελέγχου για το έγγραφο pdf |
| Button | `22000` | Ο τύπος σχολιασμού που προσθέτει κουμπί για έγγραφο pdf |
| TextSquiggly | `2500` | Ο τύπος σχολιασμού που επιλέχθηκε σιχαμένος και σχολιάζει text |
| SearchText | `2700` | Ο τύπος σχολιασμού που αναζητά κομμάτι κειμένου στο document |
| All | `7FFFFFFF` | All |

### Παρατηρήσεις

**Μάθε περισσότερα**

* [Πώς να σχολιάσετε έγγραφα σε C#](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* [Πώς να προσθέσετε σχολιασμούς περιοχής στο C#](https://docs.groupdocs.com/display/annotationnet/Add+area+annotation)
* [Πώς να προσθέσετε σχολιασμούς βέλους στο C#](https://docs.groupdocs.com/display/annotationnet/Add+arrow+annotation)
* [Πώς να προσθέσετε σχολιασμούς απόστασης στο C#](https://docs.groupdocs.com/display/annotationnet/Add+distance+annotation)
* [Πώς να προσθέσετε σχολιασμούς έλλειψης στο C#](https://docs.groupdocs.com/display/annotationnet/Add+ellipse+annotation)
* [Πώς να προσθέσετε σχολιασμούς συνδέσμων στο C#](https://docs.groupdocs.com/display/annotationnet/Add+link+annotation)
* [Πώς να προσθέσετε σχολιασμούς σημείων στο C#](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)
* [Πώς να προσθέσετε σχολιασμούς πολυγραμμών στο C#](https://docs.groupdocs.com/display/annotationnet/Add+polyline+annotation)
* [Πώς να προσθέσετε σχολιασμούς επεξεργασίας πόρων στο C#](https://docs.groupdocs.com/display/annotationnet/Add+resource+redaction+annotation)
* [Πώς να προσθέσετε σχολιασμούς πεδίων κειμένου στο C#](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)
* [Πώς να προσθέσετε σχολιασμούς επισήμανσης στο C#](https://docs.groupdocs.com/display/annotationnet/Add+highlight+annotation)
* [Πώς να προσθέσετε σχολιασμούς επεξεργασίας κειμένου στο C#](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)
* [Πώς να προσθέσετε σχολιασμούς αντικατάστασης στο C#](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)
* [Πώς να προσθέσετε σχολιασμούς διαγραφής στο C#](https://docs.groupdocs.com/display/annotationnet/Add+strikeout+annotation)
* [Πώς να προσθέσετε υπογραμμισμένους σχολιασμούς στο C#](https://docs.groupdocs.com/display/annotationnet/Add+underline+annotation)
* [Πώς να προσθέσετε σχολιασμούς υδατογραφήματος στο C#](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)
* [Πώς να προσθέσετε σχολιασμούς εικόνας στο C#](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Annotation.Options](../../groupdocs.annotation.options)
* συνέλευση [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
