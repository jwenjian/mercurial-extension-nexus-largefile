# mercurial-extension-nexus-largefile
A mercurial extension that pull large file from nexus server, uncompress and move to desired destination

- Only download from nexus server, upload to nexus server is out of scope
- A yaml configuration file
  - nexus server url
  - username
  - password (tricky part)
  - ssl (also a tricky part)
  - proxy (still tricky)
  - repository name
  - list of artifacts
    - group id, artifact id, version
    - destination path
    - password when uncompress(emm.. security is always a tricky part)
   
TBC

- How to diff?
- How to cache?
- How to know if to override the files if destinition already have the files, maybe add a configuration on never override / always override?
