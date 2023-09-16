# Literature Review Methodology

## Overall Summary

In order to find as many papers that perform security and privacy attacks or defenses on XR devices, we queried Google Scholar, ACM, and IEEE libraries,  on February 1, 2023. 

For the Google Scholar search, we identified the top 60 venues we wanted to target using the Top Publications rankings from CSRankings. Then, we searched through the papers published in those venues since 2015 which contained a set of terms anywhere in the document using Google Scholar's Advanced Search. This search resulted in 131 potential papers. Additionally, to find papers directly related to our topic that could have been published in any other venue, we followed the same search idea in ACM Digital Library, and IEEE Xplore Library, resulting in 319 potential papers.

From 319 potential papers, we have restricted our selection to 40 papers, listed in full_list_of_papers.md, testing practical attacks and their defenses that target XR devices' security and privacy. We further detail our literature review methodology in the subsections.

 ## Venues Considered for Google Scholar Search. 
For venue selection, we used [CSRankings](https://scholar.google.com/citations?view_op=top_venues) where we selected *Engineering and Computer Science* as the category, a similar approach was followed in other survey papers[1]. This presented different subcategories of venues, and we selected the ones related to security and privacy and AR/VR/MR devices. 

Hence, we chose:
* Computer Security & Cryptography: security and privacy attacks are directly related to computer security
* Computer Graphics: AR/VR/MR devices utilize computer graphics in their design
*  Human-Computer Interaction: AR/VR/MR devices are about humans interacting with computer-generated environments and objects
  
As each category contained the top 20 venues, this resulted in 60 total venues for which we analyzed submissions. The list of all venues considered can be found in list_all_venues.md in this repository. 

## ACM, CCS, IEEE Workshop Libraries Search.
In addition to the top 60 venues that we searched for using CSRankings, we also wanted to examine the published papers that were directly related to our topic but were not included in the top 60 venues. With this, we tried to eliminate bias that would have occurred due to only focusing on the top venues. For this purpose, we also queried ACM Digital Library, and IEEE Xplore using the terms that are detailed in the following section. 


## Terms Considered.
We define terms as the words that we looked for when we were finding published papers and set of terms as the combinations of words. With the set of terms, we aim to find all relevant papers that are proposing security and privacy attacks or their defenses on AR/VR/MR devices. We selected the terms by first understanding how the Advanced Search options operate. For Google Scholar the **exact phase** bar we wrote the terms that we wanted to be present in the paper that must be included in the exact order we wrote the term. Furthermore, we used **with all of the words** search bar, to yield papers that included all of the terms that we chose in the paper. To span all possible words, we used OR operations which are identifiable by the Advanced Search options offered in Google Scholar, ACM Digital Library, IEEE, and CCS. 

Table 1 shows the set of terms that are used for literature paper searches. The table is based on Boolean logic operations AND and OR, where each phrase in Term-1 can be combined with terms in the Term-2 column. Additionally, the terms in each column are combined with OR operations. With this idea, it returns articles that contain at least one term from each column anywhere in the document. In order to find papers that are directly in the scope of our SoK, we conducted our advanced searches by searching these terms inside the abstracts of the papers.

| Term-1                   |                      | Term-2          |
|----------------------------|----------------------|-------------------|
| augmented reality          | AND                  | security          |
| virtual reality            |                      | privacy           |
| mixed reality              |                      | security attack   |
| head-mounted display       |                      | privacy attack    |
| extended reality           |                      | security defense  |
| augmented reality devices  |                      | privacy defense   |
| virtual reality devices    |                      | defense           |
| mixed reality devices      |                      | attack            |
| holographic display        |                      |                   |

### Table 1: Identified Set of Terms for Literature Review Search

## Eligibility Criteria.
The search strategy yielded 319 potential papers (131 from Google Scholar, 123 from ACM Digital Library, 65 from IEEE Xplore) and we checked if they met our elimination criteria. This step was done manually and no automation tool was utilized. To check if it met the criteria, one author read the abstracts of the papers in detail and read through the papers if the abstracts weren't enough to get an understanding of the paper. The elimination criteria are given below:


* *Eligibility Criteria-1:* Is the article related to the security and/or privacy of XR devices? If not, exclude the paper from the list.
 
* *Eligibility Criteria-2:* Is the article only proposing an authentication model, without going into the details of possible attacks that can be done on the devices? If yes, exclude the paper from the list.


This criteria alone eliminated the majority of the papers. This is due to several factors. For instance, we realized during the elimination of the papers that, the initial set of potential papers (once all the duplicates are removed) also contained articles that are not related to XR devices. Such as some had a scope of AR apps in smartphones [2], tested their proposed method on a smartphone [3], or used a dataset not obtained through an XR device [4]. Additionally, the first set of papers contained many articles that weren't directly related to the devices' or the users' security and privacy, or not going into depth on the attacks and defenses, such as [4-6]. We also removed 9 additional papers from the first potential papers list that were either a magazine version of the conference paper that was also included in the list or papers that were only expanding the work done on a paper that was already included in the list [7].


## References
- [1] Stephenson, Sophie, et al. "Sok: Authentication in augmented and virtual reality." 2022 IEEE Symposium on Security and Privacy (SP). IEEE, 2022.

- [2] Harborth, David, and Alisa Frik. "Evaluating and redefining smartphone permissions with contextualized justifications for mobile augmented reality apps." Seventeenth Symposium on Usable Privacy and Security (SOUPS 2021). 2021.

- [3] Ilyena Hirskyj-Douglas, Anna Kantosalo, Andrés Monroy-Hernández, Joelle Zimmermann, Michael Nebeling, and Mar Gonzalez-Franco. 2020. Social AR: Reimagining and Interrogating the Role of Augmented Reality in Face to Face Social Interactions. In Conference Companion Publication of the 2020 on Computer Supported Cooperative Work and Social Computing (CSCW '20 Companion). Association for Computing Machinery, New York, NY, USA, 457–465. https://doi.org/10.1145/3406865.3418585

- [4] Gautham Ramajayam, Tao Sun, Chiu C. Tan, Lannan Luo, and Haibin Ling. 2023. Saliency-Aware Privacy Protection in Augmented Reality Systems. In Proceedings of the First Workshop on Metaverse Systems and Applications (MetaSys '23). Association for Computing Machinery, New York, NY, USA, 1–6. https://doi.org/10.1145/3597063.3597358
  
- [5] Freeman, Guo, et al. "Disturbing the peace: Experiencing and mitigating emerging harassment in social virtual reality." Proceedings of the ACM on Human-Computer Interaction 6.CSCW1 (2022): 1-30.

- [6] Ilyena Hirskyj-Douglas, Anna Kantosalo, Andrés Monroy-Hernández, Joelle Zimmermann, Michael Nebeling, and Mar Gonzalez-Franco. 2020. Social AR: Reimagining and Interrogating the Role of Augmented Reality in Face to Face Social Interactions. In Conference Companion Publication of the 2020 on Computer Supported Cooperative Work and Social Computing (CSCW '20 Companion). Association for Computing Machinery, New York, NY, USA, 457–465. https://doi.org/10.1145/3406865.3418585
  
- [7] Moore, Alec G., et al. "Personal identifiability of user tracking data during VR training." 2021 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW). IEEE, 2021.

