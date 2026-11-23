# Evaluating U-Net Based Architectures for Post-Treatment GliomaSegmentation
### Name : Kaveesh Wathukarawatte

## Research Overview
We are planning on investigating and evaluating U-Net based neural architectures for brain tumor segmentation in MRI scans, specifically glioma in post-treatment scans. Accurately segmenting regions of the glioma is crucial for treatment, and manual segmentation is time consuming and prone to human errors. Our goal is to explore and investigate U-Net architectures specifically for this task and improve the architectures reasonably.

## Dataset
The project will primarily focus on the BraTS 2024 Adult Glioma Post-Treatment dataset.
The MRI modalities include:
  - T1-weighted
  - T1-contrast enhanced
  - T2-weighted
  - T2-FLAIR

## Programming Language and Tools
Our main programming language is going to be python, and we will be working with pytorch. There will also be other necessary python libraries such as Numpy, Matplotlib etc.

## Intial Checklist
  - [x] Learn about the dataset, MRI modalities and brain tumor segmentation.
  - [x] Study U-Net and existing U-Net implementations for brain tumor segmentation
  - [ ] Implement a baseline segmentation and evaluate performance

## Next Steps
I plan on reading existing U-Net based architectures, specifically about FFLUNet, which is an architecture focused on efficiency, and implementing their code on our dataset.

## Reflection

 - What is a commit
    * A commit is a saved snapshot of a change made to a file or some files in the repository.
 - Why might you use a branch instead of editing main directly?
    * So that we can freely try new additions or changes to our code without affecting the main working project. Then after checking whether it is appropriate, we can later merge the branch into main if necessary.
 - How does an issue differ from a pull request?
    * An issue is used to keep track of bugs, future ideas, or problems, while a pull request is an editor of a branch requesting for the main branch to review and accept their changes to the relevant files.
