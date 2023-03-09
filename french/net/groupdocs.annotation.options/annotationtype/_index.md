---
title: AnnotationType
second_title: Référence de l'API GroupDocs.Annotation pour .NET
description: Énumération qui décrit les types dannotations pris en charge par GroupDocs.Annotation pour .NET
type: docs
weight: 960
url: /fr/net/groupdocs.annotation.options/annotationtype/
---
## AnnotationType enumeration

Énumération qui décrit les types d'annotations pris en charge par GroupDocs.Annotation pour .NET

```csharp
[Flags]
public enum AnnotationType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Valeur par défaut |
| Area | `2` | Le type d'annotation de zone qui met en évidence la zone rectangulaire dans la page de document |
| Arrow | `4` | Le type d'annotation qui dessine une flèche sur la page du document |
| Distance | `8` | Le type d'annotation qui mesure la distance entre les éléments d'une page de document |
| Ellipse | `10` | L'annotation de forme elliptique qui marque des parties du contenu du document |
| Link | `20` | Le type d'annotation qui représente un lien hypertexte vers une ressource distante |
| Point | `40` | Le type d'annotation ponctuelle qui colle un commentaire à n'importe quel endroit dans la page du document |
| Polyline | `80` | Le type d'annotation polyligne qui permet d'ajouter des formes de dessin et des lignes à main levée à une page de document |
| ResourcesRedaction | `100` | Le type d'annotation qui masque le contenu textuel derrière un rectangle noir |
| TextField | `200` | Le type d'annotation de champ de texte représente un commentaire textuel à l'intérieur d'un cadre coloré |
| TextHighlight | `400` | Le type d'annotation qui met en surbrillance et commente le texte sélectionné |
| TextRedaction | `800` | Le type d'annotation qui remplit une partie du texte sélectionné avec un rectangle noir. |
| TextReplacement | `1000` | Le type d'annotation qui remplace le texte d'origine par un autre fragment de texte fourni |
| TextStrikeout | `2000` | Le type d'annotation qui marque le fragment de texte avec un style barré |
| TextUnderline | `4000` | Le type d'annotation qui marque le texte avec un style souligné |
| Watermark | `8000` | Le type d'annotation qui ajoute un filigrane textuel sur la page de document |
| Image | `10000` | Le type d'annotation qui ajoute une superposition d'image sur le contenu de la page du document |
| Dropdown | `20000` | Le type de composant qui ajoute un composant déroulant pour le document pdf**seul** |
| Checkbox | `21000` | Le type d'annotation qui ajoute une case à cocher pour le document pdf |
| Button | `22000` | Le type d'annotation qui ajoute un bouton pour le document pdf |
| TextSquiggly | `2500` | Le type d'annotation qui serpente et commente le texte sélectionné |
| SearchText | `2700` | Le type d'annotation qui recherche le fragment de texte dans le document |
| All | `7FFFFFFF` | Tous |

### Remarques

**Apprendre encore plus**

* [Comment annoter des documents en C#](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* [Comment ajouter des annotations de zone en C#](https://docs.groupdocs.com/display/annotationnet/Add+area+annotation)
* [Comment ajouter des annotations fléchées en C#](https://docs.groupdocs.com/display/annotationnet/Add+arrow+annotation)
* [Comment ajouter des annotations de distance en C#](https://docs.groupdocs.com/display/annotationnet/Add+distance+annotation)
* [Comment ajouter des annotations d'ellipse en C #](https://docs.groupdocs.com/display/annotationnet/Add+ellipse+annotation)
* [Comment ajouter des annotations de lien en C#](https://docs.groupdocs.com/display/annotationnet/Add+link+annotation)
* [Comment ajouter des annotations de points en C#](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)
* [Comment ajouter des annotations polylignes en C#](https://docs.groupdocs.com/display/annotationnet/Add+polyline+annotation)
* [Comment ajouter des annotations de rédaction de ressources en C #](https://docs.groupdocs.com/display/annotationnet/Add+resource+redaction+annotation)
* [Comment ajouter des annotations de champ de texte en C#](https://docs.groupdocs.com/display/annotationnet/Add+text+field+annotation)
* [Comment ajouter des annotations de surbrillance en C #](https://docs.groupdocs.com/display/annotationnet/Add+highlight+annotation)
* [Comment ajouter des annotations de rédaction de texte en C#](https://docs.groupdocs.com/display/annotationnet/Add+text+redaction+annotation)
* [Comment ajouter des annotations de remplacement en C#](https://docs.groupdocs.com/display/annotationnet/Add+replacement+annotation)
* [Comment ajouter des annotations barrées en C #](https://docs.groupdocs.com/display/annotationnet/Add+strikeout+annotation)
* [Comment ajouter des annotations de soulignement en C #](https://docs.groupdocs.com/display/annotationnet/Add+underline+annotation)
* [Comment ajouter des annotations de filigrane en C#](https://docs.groupdocs.com/display/annotationnet/Add+watermark+annotation)
* [Comment ajouter des annotations d'image en C#](https://docs.groupdocs.com/display/annotationnet/Add+image+annotation)

### Voir également

* espace de noms [GroupDocs.Annotation.Options](../../groupdocs.annotation.options)
* Assemblée [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
