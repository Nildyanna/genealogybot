# GenealogyBot

A personal, non-commercial desktop app for one person's own family-history research. It runs entirely on the
owner's Windows PC with a local AI model: no cloud service, no account, no data sent to anyone.

## What it does
- Keeps a family tree on the owner's PC and edits it from conversation, with every change undoable.
- Checks the tree for impossible dates and broken links.
- Searches public sources (web, Library of Congress, Internet Archive) and, with the user's own sign-in,
  FamilySearch, to find leads for people **already in the tree**.
- Shows what it finds, with the source address, for the owner to review. Nothing found online is added to the
  tree without a source, and research results wait for the owner's approval.

## FamilySearch use
- **Read-only.** It uses the FamilySearch Tree API for person search and person lookups. It never creates,
  edits or deletes anything on FamilySearch.
- **Signs in with FamilySearch's own OAuth page** (authorization code with PKCE). The app never sees a password;
  it keeps only the access token on the owner's PC.
- **Single user, personal use.** It is not offered to others and does not store, aggregate or share
  FamilySearch data beyond the owner's own local research tree.
- Results are treated as leads: other users' tree entries are not proof, and the owner reviews them.

## Privacy
Everything is stored in a local folder on the owner's PC. Web searches send only the search words to the search
engine; no tree data is uploaded. Living people are not researched.

## Status
Personal project, not released as a product. Contact: the repository owner.
