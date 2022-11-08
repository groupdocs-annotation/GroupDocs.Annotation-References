---
title: Annotator
second_title: Référence de l'API GroupDocs.Annotation pour .NET
description: Représente la classe principale qui contrôle le processus dannotation de document.
type: docs
weight: 10
url: /fr/net/groupdocs.annotation/annotator/
---
## Annotator class

Représente la classe principale qui contrôle le processus d'annotation de document.

```csharp
public class Annotator : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Annotator](annotator#constructor)(Stream) | Initialise la classe d'annotateur qui accepte le flux de documents |
| [Annotator](annotator#constructor_4)(string) | Initialise la classe d'annotateur qui accepte le chemin du document |
| [Annotator](annotator#constructor_1)(Stream, AnnotatorSettings) | Initialise la classe d'annotateur qui accepte le flux de documents |
| [Annotator](annotator#constructor_2)(Stream, LoadOptions) | Initialise la classe d'annotateur qui accepte le flux de documents |
| [Annotator](annotator#constructor_5)(string, AnnotatorSettings) | Initialise la classe d'annotateur qui accepte le chemin du document |
| [Annotator](annotator#constructor_6)(string, LoadOptions) | Initialise la classe d'annotateur qui accepte le chemin du document |
| [Annotator](annotator#constructor_3)(Stream, LoadOptions, AnnotatorSettings) | Initialise la classe d'annotateur qui accepte le flux de documents |
| [Annotator](annotator#constructor_7)(string, LoadOptions, AnnotatorSettings) | Initialise la classe d'annotateur qui accepte le chemin du document |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../groupdocs.annotation/annotator/document) { get; } | Document |
| [ProcessPages](../../groupdocs.annotation/annotator/processpages) { get; set; } | Pages de documents |
| [Rotation](../../groupdocs.annotation/annotator/rotation) { get; set; } | Rotation des documents |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../groupdocs.annotation/annotator/add#add)(AnnotationBase) | Ajoute une annotation au document |
| [Add](../../groupdocs.annotation/annotator/add#add_1)(List&lt;AnnotationBase&gt;) | Ajoute une collection d'annotations à un document. |
| [Dispose](../../groupdocs.annotation/annotator/dispose)() | Éliminer |
| [ExportAnnotationsFromXMLFile](../../groupdocs.annotation/annotator/exportannotationsfromxmlfile)(string) | Exporter les annotations du fichier XML. |
| [Get](../../groupdocs.annotation/annotator/get#get)() | Obtient des collections d'annotations de document. |
| [Get](../../groupdocs.annotation/annotator/get#get_1)(AnnotationType) | Obtient une collection d'annotations de document par type d'annotation. |
| [GetVersion](../../groupdocs.annotation/annotator/getversion)(object) | Obtenir des annotations à partir des versions. |
| [GetVersionsList](../../groupdocs.annotation/annotator/getversionslist)() | Obtenir les versions. |
| [ImportAnnotationsFromDocument](../../groupdocs.annotation/annotator/importannotationsfromdocument)(string) | Importer des annotations d'un document vers un fichier XML. |
| [Remove](../../groupdocs.annotation/annotator/remove#remove)(AnnotationBase) | Supprime l'annotation du document. |
| [Remove](../../groupdocs.annotation/annotator/remove#remove_1)(int) | Supprime l'annotation du document par Id. |
| [Remove](../../groupdocs.annotation/annotator/remove#remove_2)(List&lt;AnnotationBase&gt;) | Supprime la collection d'annotations du document. |
| [Remove](../../groupdocs.annotation/annotator/remove#remove_3)(List&lt;int&gt;) | Supprime la collection d'annotations du document par les identifiants d'annotation fournis. |
| [Save](../../groupdocs.annotation/annotator/save#save)() | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Save](../../groupdocs.annotation/annotator/save#save_1)(SaveOptions) | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Save](../../groupdocs.annotation/annotator/save#save_2)(Stream) | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Save](../../groupdocs.annotation/annotator/save#save_4)(string) | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Save](../../groupdocs.annotation/annotator/save#save_3)(Stream, SaveOptions) | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Save](../../groupdocs.annotation/annotator/save#save_5)(string, SaveOptions) | Enregistre le document après avoir ajouté, mis à jour ou supprimé des annotations. |
| [Update](../../groupdocs.annotation/annotator/update#update)(AnnotationBase) | Met à jour l'annotation du document. |
| [Update](../../groupdocs.annotation/annotator/update#update_1)(List&lt;AnnotationBase&gt;) | Met à jour la collection d'annotations de documents. |

### Voir également

* espace de noms [GroupDocs.Annotation](../../groupdocs.annotation)
* Assemblée [GroupDocs.Annotation](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Annotation.dll -->
