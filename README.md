# NostrGit

a truly censorship-resistant alternative to GitHub that has a chance of working

- [Next.js](https://nextjs.org)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

![frontpage](https://github.com/cypherhoodlum/NostrGit/blob/detailed_readme/src/resources/frontpage.png)

# Development

Fork the repo

```bash
# install npm packages
$ npm i
# run in development mode (localhost:3000)
$ npm run dev
```

# Roadmap

Implement the UI similar to the reference pictures.

UI
- [ ] Code
    - [ ] Clone with HTTPS
    - [ ] Clone with SSH
    - [ ] Download ZIP
- [ ] Issues
    - [ ] Issues list
        - [ ] Filter by open / closed issues
    - [ ] Single issue
        - [ ] Show details about the issue
        - [ ] Commenting / comment threads
    - [ ] New issue page
- [ ] Pull Requests
    - [ ] Pull requests list
    - [ ] Single pull request page
    - [ ] New pull request page
- [ ] Discussions
- [ ] Insights
    - [ ] Repo statistics
        - Merged pull requests
        - Open pull requests
        - Closed issues
        - New issues
    - [ ] Tabs
        - [ ] Contributors
        - [ ] Commits
        - [ ] Code frequency
        - [ ] Dependency graph
        - [ ] Forks
- [ ] Settings
    - [ ] Edit repository name
    - [ ] Toggle features
        - Wikis
        - Issues
        - Discussions
        - Pull requests
            - Allow merge commits
            - Allow squash merging
            - Allow rebase merging
    - [ ] Danger zone
        - Change repo visibility
        - Transfer ownership
        - Delete repo
    - [ ] Settings tabs
        - [ ] General
        - [ ] Access (collaborators)
            - [ ] View collaborators
            - [ ] Add collaborators
            - [ ] Remove collaborators
        - [ ] Branches
            - [ ] Branch protection rules
        - [ ] Tags
        - [ ] Actions
        - [ ] Secrets and variables
    

Nostr
- [ ] Login
- [ ] Figure out decentralised data storage
