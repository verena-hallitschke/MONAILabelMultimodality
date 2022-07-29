# NOTICE

This is a modified version of the [MONAILabel repository](https://github.com/Project-MONAI/MONAILabel). This file contains overview of all changed files in this repository.

## Root directory

* [`README.md`](./README.md): [Adapted] to contain information on the changes made in this repository.
* [`NOTICE.md`](./NOTICE.md): [Added], contains information on the changes made

## plugins/slicer
* [`MONAILabelMultimodality`](./plugins/slicer/MONAILabelMultimodality): [Adapted] copy of [`MONAILabel`](./plugins/slicer/MONAILabel), adapted to support and display two modalities. The following files were updated:
  - [`MONAILabelMultimodality/MONAILabel.py`](./plugins/slicer/MONAILabelMultimodality/MONAILabel.py)
  - [`MONAILabelMultimodality/Resources/Icons/fg_green.png`](./plugins/slicer/MONAILabelMultimodality/Resources/Icons/fg_green.png)
  - [`MONAILabelMultimodality/Resources/UI/MONAILabel.ui`](./plugins/slicer/MONAILabelMultimodality/Resources/UI/MONAILabel.ui)
* [`MONAILabelSingleView`](./plugins/slicer/MONAILabelSingleView), note that this is a renamed and adapted copy of [`MONAILabel/: [Adapted] copy of [`MONAILabel`](./plugins/slicer/MONAILabel), adapted to support two modalities, allowing to switch the displayed modality with a button. The following files were updated: 
  - [`MONAILabelSingleView/MONAILabelSingleView.py`](./plugins/slicer/MONAILabelSingleView/MONAILabelSingleView.py), note that this is a renamed and adapted copy of [`MONAILabel/MONAILabel.py`](./plugins/slicer/MONAILabel/MONAILabel.py)
  - [`MONAILabelSingleView/Resources/Icons/fg_green.png`](./plugins/slicer/MONAILabelSingleView/Resources/Icons/fg_green.png)
  - [`MONAILabelSingleView/Resources/UI/MONAILabel.ui`](./plugins/slicer/MONAILabelSingleView/Resources/UI/MONAILabel.ui)

All other files are exact copies of the original files of the same name.