# Eclipse Sirius Metaeditor
Landing page and central issue tracker for our Eclipse Sirius Meta Editor.

## Requirements
[Eclipse Modeling Tools](https://www.eclipse.org/downloads/packages/) (tested with Eclipse 2021-03) with installed [Eclipse Sirius](https://www.eclipse.org/sirius/), [Acceleo](https://www.eclipse.org/acceleo), and [QVTo](https://projects.eclipse.org/projects/modeling.mmt.qvt-oml).

## Metamodels (require Eclipse Modeling Tools)
All metamodels can be found in the [sirius-meta-editor-ecore-metamodels](https://github.com/tuiSSE/sirius-meta-editor-ecore-metamodels) repository.

## Sirius Editor (requires Eclipse Sirius)
The Viewpoint specification Project for the Sirius metaeditor can be found [here](https://github.com/tuiSSE/sirius-meta-editor-sirius-metaeditor).
This editor can be used for graphically creating DomainDescription (.architecture) models.

## Transformations
### Model-to-model (M2M) Transformations (require QVTo)
* [Architecture2Ecore](https://github.com/tuiSSE/sirius-meta-editor-architecture2ecore)
* [Architecture2Sirius](https://github.com/tuiSSE/sirius-meta-editor-architecture2sirius)

### Model-to-text (M2T) Transformation (requires Acceleo)
* [Architecture2SiriusText](https://github.com/tuiSSE/sirius-meta-editor-architecture2siriustext)

## Literature
_A generative Approach for creating Eclipse Sirius Editors for generic Systems_ - Syscon 2021, F. Bedini, R. Maschotta, and A. Zimmermann

## Acknowledgment
This work has received funding from the _[Carl Zeiss Foundation](https://www.carl-zeiss-stiftung.de/english/index.html)_ as part of the project ``Engineering for Smart Manufacturing'' ([E4SM](https://e4sm-projekt.de)) under grant agreement no. P2017-01-005.
