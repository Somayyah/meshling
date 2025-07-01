# meshling
Small local internet for my needs only. 

### 🗂️ Phase 1: Build Your Offline Library

* [ ] Collect and catalog all PDFs, ebooks, offline website archives
* [ ] Download and archive key websites (CPP reference, Hacker Notes, foraging, mycology, gardening, recipes)
* [ ] Strip ads, scripts, trackers from saved HTML to keep it clean and fast
* [ ] Organize files by topic, version, and source for easy retrieval
* [ ] Back up library to external HDD or RAID enclosure (encrypted if possible)
* [ ] Create a simple directory index or HTML portal page to browse content offline

---

### 🔌 Phase 2: Serve Your Content Locally

* [ ] Set up a lightweight HTTP server (start with Python’s http.server for dev)
* [ ] Experiment with Apache or Nginx to serve the library without JS or ads, optional and only attempt when you actually need it!
* [ ] Disable unnecessary services and JavaScript for speed and safety
* [ ] Design simple navigation pages for easier use on LAN
* [ ] Document manual steps to run the server on different machines (Pi, old laptop)
* [ ] Test access on various devices (phone, tablet, PC) on local network

---

### ⚙️ Phase 3: Automation and Reproducibility

* [ ] Write scripts (bash, Python, batch) to automate:

  * Content download & update
  * Library cleanup (strip JS/ads)
  * Server setup and configuration
* [ ] Build initial config files for HTTP server and indexing pages
* [ ] Version control your scripts and config files (GitLab/GitHub/self-hosted)
* [ ] Document setup and update process clearly and simply
* [ ] Share public repo with initial scripts and readme

---

### 🔒 Phase 4: Security & Encryption

* [ ] Implement disk encryption on your library storage (LUKS or VeraCrypt)
* [ ] Learn PGP/GPG basics for signing and encrypting files
* [ ] Sign your content hashes and configuration files for integrity checks
* [ ] Explore encrypted email tools and workflows for communication (start simple)
* [ ] Document encryption setup and key management practices
* [ ] Consider automating signing and verification steps

---

### 🌐 Phase 5: Mini Internet on Local Network

* [ ] Expand server to host multiple sites or services (wiki, docs, media)
* [ ] Experiment with lightweight local DNS or hosts file for domain-like navigation
* [ ] Add search functionality for your offline content (e.g., Elasticsearch, Lucene)
* [ ] Test network resilience: offline operation, low bandwidth tolerance
* [ ] Explore containerization only if/when complexity demands (keep it minimal)
* [ ] Create a fail-safe plan for restoring your mini internet from scratch

---

### 🔄 Phase 6: Maintenance & Growth

* [ ] Schedule periodic updates to offline content
* [ ] Develop scripts for syncing updates from occasional internet connection
* [ ] Monitor disk health, backups, and encryption keys regularly
* [ ] Share progress, pitfalls, and tools openly in your repo/readme
* [ ] Seek collaborators or curious minds to test or improve the setup
