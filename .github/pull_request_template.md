# Description
<!--- Briefly describe the changes included in this pull request  --->

### Closes #...  <!-- edit if this PR closes an Issue -->

# Checklist
<!--- Please read each of the following items and confirm by replacing the [ ] with a [X] --->

- [ ] This PR does NOT contain [PHI](https://ohrpp.research.ucla.edu/hipaa/) or germline genetic data.  A repo may need to be deleted if such data is uploaded. Disclosing PHI is a [major problem](https://healthitsecurity.com/news/ucla-health-reaches-7.5m-settlement-over-2015-breach-of-4.5m).
- [ ] This PR does NOT contain molecular files, compressed files, output files such as images (*e.g.* `.png`, .`jpeg`), `.pdf`, `.RData`, `.xlsx`, `.doc`, `.ppt`, or other non-plain-text files.  To automatically exclude such files using a [.gitignore](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) file, see [here](https://github.com/uclahs-cds/template-base/blob/main/.gitignore) for example.
- [ ] I have read the [code review guidelines](https://confluence.mednet.ucla.edu/display/BOUTROSLAB/Code+Review+Guidelines) and the [code review best practice on GitHub check-list](https://confluence.mednet.ucla.edu/display/BOUTROSLAB/Code+Review+Best+Practice+on+GitHub+-+Check+List).
- [ ] I have set up or verified the `main` branch protection rule following the [github standards](https://confluence.mednet.ucla.edu/pages/viewpage.action?spaceKey=BOUTROSLAB&title=GitHub+Standards#GitHubStandards-Branchprotectionrule) before opening this pull request.
- [ ] The name of the branch is meaningful and well formatted following the [standards](https://confluence.mednet.ucla.edu/display/BOUTROSLAB/Code+Review+Best+Practice+on+GitHub+-+Check+List), using [AD_username (or 5 letters of AD if AD is too long)]-[brief_description_of_branch].
- [ ] I have added the major changes included in this pull request to the `CHANGELOG.md` under the next release version or unreleased, and updated the date.

<!-- 
Admin/maintainer: please edit the remaining sections as needed for your project repo.  
Then commit/push the changes so everyone uses this template for future PRs.

For example, if your project is a `pipeline`, then create a pipeline testing results section.

If your project is a general data analysis project, then you may want to require testing results
in each PR to help prevent creating new bugs.
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
