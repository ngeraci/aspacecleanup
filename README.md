# ArchivesSpace scripts

scripts that interact with the ArchivesSpace API to automate various cleanup and export tasks (more to come).

## Authentication
for authentication, create a separate file called `secrets.py` in the following format:
```secrets.py
backendurl='your backend URL'
user='your username'
password='your password'
```

## Scripts
### alpha_subj.py
orders collection-level subject headings alphabetically, with topical, geographic and other headings grouped together first, then form/genre headings.

### aspace_cleanup.py
a giant hulking script that does a bunch of different cleanup requested in Dec. 2017 collection-level record update project, including note updates, date normalization, and container summary updates. want to eventually break it into smaller reusable pieces.

## Acknowledgements & other resources
I figured out how to do most of this by looking at similar scripts written by [Lora Woodford](https://github.com/lorawoodford/python_scripts) and at the [Rockefeller Archive Center](https://github.com/RockefellerArchiveCenter/scripts/tree/master/archivesspace).
