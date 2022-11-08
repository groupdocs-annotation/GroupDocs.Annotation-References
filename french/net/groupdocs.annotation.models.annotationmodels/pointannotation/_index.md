---
title: PointAnnotation
second_title: Référence de l'API GroupDocs.Annotation pour .NET
description: Représente les propriétés dannotation de points
type: docs
weight: 640
url: /fr/net/groupdocs.annotation.models.annotationmodels/pointannotation/
---
## PointAnnotation class

Représente les propriétés d'annotation de points

```csharp
public class PointAnnotation : AnnotationBase, IEquatable<PointAnnotation>, IPointAnnotation
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PointAnnotation](pointannotation)() | Initialise la nouvelle instance de[`PointAnnotation`](../pointannotation) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Box](../../groupdocs.annotation.models.annotationmodels/pointannotation/box) { get; set; } | Obtient ou définit la position d'annotation |
| [CreatedOn](../../groupdocs.annotation.models.annotationmodels/annotationbase/createdon) { get; set; } | Obtient ou définit la date de création de l'annotation |
| [Id](../../groupdocs.annotation.models.annotationmodels/annotationbase/id) { get; set; } | Obtient ou définit l'identificateur unique d'annotation |
| [Message](../../groupdocs.annotation.models.annotationmodels/annotationbase/message) { get; set; } | Obtient ou définit le message d'annotation |
| [PageNumber](../../groupdocs.annotation.models.annotationmodels/annotationbase/pagenumber) { get; set; } | Obtient ou définit le numéro de page à annoter |
| [Replies](../../groupdocs.annotation.models.annotationmodels/annotationbase/replies) { get; set; } | Représente la collection de réponses d'annotation |
| [Type](../../groupdocs.annotation.models.annotationmodels/annotationbase/type) { get; set; } | Obtient ou définit le type d'annotation |
| [User](../../groupdocs.annotation.models.annotationmodels/annotationbase/user) { get; set; } | Obtient ou définit le créateur d'annotations |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Clone](../../groupdocs.annotation.models.annotationmodels/pointannotation/clone)() | Renvoie une nouvelle instance avec les mêmes valeurs |
| [Equals](../../groupdocs.annotation.models.annotationmodels/annotationbase/equals)(AnnotationBase) | Compare les annotations de base à l'aide de la méthode IEquatable Equals |
| override [Equals](../../groupdocs.annotation.models.annotationmodels/pointannotation/equals#equals_2)(object) | Compare les annotations de points à l'aide de l'objet standard Égale à la méthode |
| [Equals](../../groupdocs.annotation.models.annotationmodels/pointannotation/equals#equals_1)(PointAnnotation) | Compare les annotations de points à l'aide de la méthode IEquatable Equals |
| override [GetHashCode](../../groupdocs.annotation.models.annotationmodels/pointannotation/gethashcode)() | Renvoie le code de hachage de l'annotation de point |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types d'annotations et l'annotation de documents PDF et Microsoft Word, de feuilles de calcul Excel et de présentations PowerPoint : [Comment annoter des documents à l'aide de GroupDocs.Annotation pour .NET](https://docs.groupdocs.com/display/annotationnet/Add+annotation+to+the+document)
* En savoir plus sur l'ajout d'annotations ponctuelles à des documents de différents types : [Comment ajouter des annotations de points en C#](https://docs.groupdocs.com/display/annotationnet/Add+point+annotation)

### Voir également

* class [AnnotationBase](../annotationbase)
* interface [IPointAnnotation](../../groupdocs.annotation.models.annotationmodels.interfaces.annotations/ipointannotation)
* espace de noms [GroupDocs.Annotation.Models.AnnotationModels](../../groupdocs.annotation.models.annotationmodels)
* Assemblée [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->