<table align="center">
<tr>
<td width="140" align="center">
    <img src="https://wiki.fairykey.app/assets/icon.png" alt="Fairy Key" width="128" />
</td>
<td align="left" style="vertical-align: middle;">
    <h1>Fairy Key: a virtual piano sheet scroller</h1>
</td>
</tr>
</table>

## 📘 Wiki & Documentation
This is a repo for Fairy Key's wiki: [wiki.fairykey.app](https://wiki.fairykey.app/)

## Contributing
The wiki uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to handle displaying content and deploying through Github Actions.

Changes to wiki pages can be made directly from Github from their counterpart `.md` files, or the entire repo can be cloned and pull-requested through Git.
When a commit is made, a workflow CI is setup with Github actions to deploy the site with the new build (takes a few minutes to complete after committing).

## Buiding using Windows
This project uses **Python 3.13** and **pip** to install dependencies.

**1. Clone the repository (Git)**
```
git clone https://github.com/FairyKey/wiki.git
cd wiki
```
**2. Create and activate a virtual environment (optional)**
```
python -m venv venv
venv\Scripts\activate
```
**3. Install dependencies**
```
pip install -r requirements.txt
```

MkDocs: to serve and preview the site at any time locally (accessible at [http://127.0.0.1:8000](http://127.0.0.1:8000)) 
```
mkdocs serve
```
