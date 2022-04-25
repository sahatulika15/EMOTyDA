# Emotion aware Dialogue Act : EMOTyDA

## This is the readme file that contains the information about the EMOTyDA dataset introduced in the following paper

**Paper Name:-** Towards Emotion-aided Multi-modal Dialogue Act Classification
>The task of Dialogue Act Classification (DAC) that purports to capture communicative intent has been studied extensively. But these studies limit themselves to text. Non-verbal features (change of tone, facial expressions etc.) can provide cues to identify DAs, thus stressing the benefit of incorporating multi-modal inputs in the task. Also, the emotional state of the speaker has a substantial effect on the choice of the dialogue act, since conversations are often influenced by emotions. Hence, the effect of emotion too on automatic identification of DAs needs to be studied. In this work, we address the role of both multi-modality and emotion recognition (ER) in DAC. DAC and ER help each other by way of multi-task learning. One of the major contributions of this work is a new dataset- multimodal Emotion aware Dialogue Act dataset called EMOTyDA, collected from open-sourced dialogue datasets. To demonstrate the utility of EMOTyDA, we  build an attention based (self, inter-modal, inter-task) multi-modal, multi-task Deep Neural Network (DNN) for joint learning of DAs and emotions. We show empirically that multi-modality and multi-tasking achieve better performance of DAC compared to uni-modal and single task DAC variants.

* **Authors:** Tulika Saha, Aditya Patra, Sriparna Saha and Pushpak Bhattacharyya
* **Affiliation:** Indian Institute of Technology Patna, India
* **Corresponding Author:** [Tulika Saha](sahatulika15@gmail.com)
* **Accepted(July, 2020):**  [Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics(ACL)](https://www.aclweb.org/anthology/2020.acl-main.402/)

If you consider this dataset useful, please cite it as

```bash
@inproceedings{saha-etal-2020-towards,
    title = "Towards Emotion-aided Multi-modal Dialogue Act Classification",
    author = "Saha, Tulika  and
      Patra, Aditya  and
      Saha, Sriparna  and
      Bhattacharyya, Pushpak",
    booktitle = "Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.acl-main.402",
    doi = "10.18653/v1/2020.acl-main.402",
    pages = "4361--4372",
}
```

# Description

1. EMOTyDA dataset is curated by collecting conversations from two open sourced datasets IEMOCAP and MELD.
2. Both IEMOCAP and MELD have pre-annotated emotion labels.
3. The 12 DA annotated catefories are "Greeting (g)", "Question (q)", "Answer (ans)", "Statement-Opinion (o)", "Statement-Non-Opinion (s)", "Apology (ap)", "Command (c)", "Agreement (ag)", "Disagreement (dag)",  "Acknowledge (a)", "Backchannel (b)" and "Others (oth)".
4. The videos of the transcript can be downloaded from the source dataset : https://github.com/SenticNet/MELD , https://sail.usc.edu/iemocap/iemocap_release.htm

# Contact

For any queries, feel free to contact the corresponding author Tulika Saha (sahatulika15@gmail.com)
