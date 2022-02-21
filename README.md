The [**Knowledge Representation and Reasoning research group (KRR)**](https://www.cardiff.ac.uk/research/explore/research-units/cardiff-knowledge-representation-and-reasoning) at Cardiff University aims to develop novel methods for capturing, modelling and reasoning about knowledge encoded in symbolic or sub-symbolic forms. We also have a particular interest in research that crosses the boundaries of various AI fields, including Neuro-Symbolic reasoning, commonsense reasoning, and representation learning.
We offer expertise in: **Ontology-enhanced Systems**, **Knowledge Graphs**, **Temporal and Probabilistic Reasoning**,  **Neuro-symbolic Reasoning**, **Non-monotonic Reasoning**, **Belief change**, **Controlled Natural Language**, **Computational Social Choice**.

*The Page is built on top of the templates provided by [**UCL DARK Lab**](https://dark.cs.ucl.ac.uk/).*

## Update your information
Edit `sitedata/people.yml`

* `interests:` Your research interests. Can be a single sentence or keywords seperated by `;`
* `home:` Homepage
* `tw:` Twitter handle
* `im:` Your photo. It can either be a web link or the link to the picture under `static/images/people/`
* `github:` Your GitHub acount name

## Steps to add your papers

### On commandline:
0. `git pull origin`
1. Append a new row to `sitedata/papers.csv`
2. Add an image of the paper to `static/images/papers`
    * file name should be "[YOUR PAPER UID].jpg" (png format not supported currently)
    * the file size should be less than 500kb
3. `make run` to check the updates locally
4. `git add static/images/papers`
5. `git commit -am "[YOUR MSG]"`
6. `git push origin`


## Add a news
### On commandline:
0. `git pull origin`
1. Append a new item to `sitedata/news.yml`
    * message is in markdown format
2. `make run` to check the updates locally
3. `git add static/images/papers`
4. `git commit -am "[YOUR MSG]"`
5. `git push origin`



## Steps to update the site
The following steps are optional (in case you want your modifications show immediately on the https://ckkr2cardiff.github.io/) :
`bash deploy.sh`
