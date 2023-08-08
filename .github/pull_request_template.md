# Description
<!--- Briefly describe the changes included in this pull request  --->

### Closes #...  <!-- edit if this PR closes an Issue -->

<!-- 
Admin/maintainer: please edit the 'Pipeline Run Results' or 'Analysis Results' sections as needed for your project repo.  
Then commit/push the changes so everyone uses this template for future PRs.

For example, if your project is a `pipeline`, then create a 'Pipeline Run Results' section.

If your project is a general data analysis project, then you may want to require an 'Analysis Results' section in order to test
code from each PR to help prevent creating new bugs.
-->

## Pipeline Run Results

- Case 1
    - sample:    <!-- e.g. A-mini S2.T-1, A-mini S2.T-n1 -->
    - input csv: <!-- path/to/input.csv -->
    - config:    <!-- path/to/xxx.config -->
    - output:    <!-- path/to/output -->
    - log:       <!-- path/to/log -->
- Case 2
    - sample:    <!-- e.g. A-mini S2.T-1, A-mini S2.T-n1 -->
    - input csv: <!-- path/to/input.csv -->
    - config:    <!-- path/to/xxx.config -->
    - output:    <!-- path/to/output -->
    - log:       <!-- path/to/log -->

## Analysis Results

- Case 1
    - script:    <!-- path/to/script.R -->
    - command:   <!-- path/to/launch.sh -->
    - output:    <!-- path/to/output -->
- Case 2
    - script:    <!-- path/to/script.R -->
    - command:   <!-- path/to/launch.sh -->
    - output:    <!-- path/to/output -->

# Checklist
<!--- Please read each of the following items and confirm by replacing the [ ] with a [X] --->

- [ ] This PR **does *NOT* contain** Protected Health Information [(PHI)](https://ohrpp.research.ucla.edu/hipaa/). A repo may ***need to be deleted*** if such data is uploaded. <br> Disclosing PHI is a ***major problem***[^1] - Even ***a small leak can be costly***[^2].
  
- [ ] This PR **does *NOT* contain** germline genetic data[^3], RNA-Seq, DNA methylation, microbiome or other molecular data[^4].

[^1]: [UCLA Health reaches $7.5m settlement over 2015 breach of 4.5m patient records](https://healthitsecurity.com/news/ucla-health-reaches-7.5m-settlement-over-2015-breach-of-4.5m)
[^2]: [The average healthcare data breach costs $2.2 million, despite the majority of breaches releasing fewer than 500 records.](https://www.ponemon.org/local/upload/file/Sixth%20Annual%20Patient%20Privacy%20%26%20Data%20Security%20Report%20FINAL%206.pdf)
[^3]: [Genetic information is considered PHI.](https://www.genome.gov/about-genomics/policy-issues/Privacy#:~:text=In%202013%2C%20as%20required%20by,genetic%20information%20for%20underwriting%20purposes.)
  [Forensic assays can identify patients with as few as 21 SNPs](https://www.sciencedirect.com/science/article/pii/S1525157817305962)
[^4]: [RNA-Seq](https://www.nature.com/articles/ng.2248), [DNA methylation](https://ieeexplore.ieee.org/document/7958619), [microbiome](https://www.pnas.org/doi/pdf/10.1073/pnas.1423854112), or other molecular data can be used to predict genotypes (PHI) and reveal a patient's identity.


- [ ] This PR **does *NOT* contain** other non-plain text files, such as: compressed files, images (*e.g.* `.png`, .`jpeg`), `.pdf`, `.RData`, `.xlsx`, `.doc`, `.ppt`, or other output files.

_&emsp; To automatically exclude such files using a [.gitignore](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) file, see [here](https://github.com/uclahs-cds/template-base/blob/main/.gitignore) for example._

- [ ] I have read the [code review guidelines](https://uclahs-cds.atlassian.net/wiki/spaces/BOUTROSLAB/pages/3187646/Code+Review+Guidelines) and the [code review best practice on GitHub check-list](https://uclahs-cds.atlassian.net/wiki/spaces/BOUTROSLAB/pages/3189956/Code+Review+Best+Practice+on+GitHub+-+Check+List).

- [ ] I have set up or verified the `main` branch protection rule following the [github standards](https://uclahs-cds.atlassian.net/wiki/spaces/BOUTROSLAB/pages/3190380/GitHub+Standards#GitHubStandards-Branchprotectionrule) before opening this pull request.

- [ ] The name of the branch is meaningful and well formatted following the [standards](https://uclahs-cds.atlassian.net/wiki/spaces/BOUTROSLAB/pages/3189956/Code+Review+Best+Practice+on+GitHub+-+Check+List), using [AD_username (or 5 letters of AD if AD is too long)]-[brief_description_of_branch].
  
- [ ] I have added the major changes included in this pull request to the `CHANGELOG.md` under the next release version or unreleased, and updated the date.

