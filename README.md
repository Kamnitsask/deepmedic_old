DeepMedic
=====================================

Efficient Multi-Scale 3D Convolutional Neural Network for Brain Lesion Segmentation

### News

The DeepMedic project aims at providing an easy to use tool and robust tool for segmentation of medical images with deep learning.

**We continue our efforts to maintain and extend this project.**

To better manage our efforts and workload, the repo was transferred seamlessly under its own organization.

**The repository has been transferred to:**

https://github.com/deepmedic

Please find our work and follow the new developments there. Thank you all for your interest in our work and the continuous feedback. **Keep the feedback going, it's what keeps us going :-)**


Sincerely,

Konstantinos Kamnitsas


### If you had cloned previous project, update your remote URL

Since the transfer of the repo, GitHub itself should have automatically updated the link of any **forked** projects automatically to the new location. 

If you had **cloned** the previous project from (https://github.com/kamnitsask/deepmedic), then you can seamlessly continue your workflow as follows. You simply have to change in your cloned deepmedic the URL that points to the remote location where the project lies, so that you continue pulling and pushing. For this, simply do:

```cshell
$ cd ./root/folder/of/your/cloned/deepmedic
$ git remote -v         # It will return something like the following 2 lines...
origin	https://github.com/Kamnitsask/deepmedic.git (fetch)
origin	https://github.com/Kamnitsask/deepmedic.git (push)
$ git remote set-url origin https://github.com/deepmedic/deepmedic.git
$ git remote -v         # It should now return the updated url...
origin	https://github.com/deepmedic/deepmedic.git (fetch)
origin	https://github.com/deepmedic/deepmedic.git (push)
```

Done. You can now continue pulling/pushing like normal.



### Info

This repository used to hold the code for the papers:

[1] **Konstantinos Kamnitsas**, Christian Ledig, Virginia F.J. Newcombe, Joanna P. Simpson, Andrew D. Kane, David K. Menon, Daniel Rueckert, and Ben Glocker, “[Efficient Multi-Scale 3D CNN with Fully Connected CRF for Accurate Brain Lesion Segmentation][paper1]”, *Medical Image Analysis, 2016*.

[2] **Konstantinos Kamnitsas**, Enzo Ferrante, Sarah Parisot, Christian Ledig, Aditya Nori, Antonio Criminisi, Daniel Rueckert, Ben Glocker, “[DeepMedic for Brain Tumor Segmentation][paper2]”, *Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries, MICCAI, 2016*.

[3] **Konstantinos Kamnitsas**, Liang Chen, Christian Ledig, Daniel Rueckert, and Ben Glocker, “[Multi-Scale 3D CNNs for segmentation of brain Lesions in multi-modal MRI][paper3]”, *in proceeding of ISLES challenge, MICCAI 2015*.


