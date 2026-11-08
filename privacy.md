---
layout: default
title: Privacy Notice
---

# Privacy Notice

**Application:** Personal Finance Hub  
**Owner and privacy contact:** Artem Borisov, tema.gad@gmail.com  
**Last updated:** 8 November 2026

## Scope and purpose

This private, non-commercial application is used only by its owner to collect and retain information about the owner's own bank accounts for personal financial record keeping. It does not accept other users' accounts.

## Information processed

Depending on what the bank provides, the application may retrieve account identifiers such as IBAN, account names and currencies, balances, and transaction records including amounts, dates, descriptions, counterparties and status. It retains the original provider response for each transaction, which may contain additional bank-supplied fields.

The application also stores authorization session information, expiry dates and synchronization results. It does not collect or store bank login passwords or one-time bank authentication codes.

## Providers and disclosure

Account data passes through Enable Banking to the local application following explicit authorization. Enable Banking processes account data and maintains authorization information under its own [Privacy Notice](https://tilisy.enablebanking.com/privacy) and [Terms of Service](https://tilisy.enablebanking.com/terms). The bank's own notices also apply.

The application does not sell account data or send it to advertising, analytics or external AI services. A future change involving additional recipients would require the owner's separate decision and an updated notice.

## Storage, retention and deletion

Financial records are stored in a local SQLite database. Private keys and working authorization sessions are kept separately from that database. Local files have restricted permissions; the configured computer uses disk encryption. Database backups are encrypted with a separate key. These measures reduce risk but cannot guarantee absolute security.

Records remain until the owner deletes them; there is no automatic retention deadline. Deletion must also account for retained backups and exports. Expiry or revocation of bank access does not automatically erase existing local records. The owner can stop synchronization, revoke consent through the available bank or Enable Banking controls, and delete local files and copies.

## These public document pages

These pages do not provide bank access, accept account data or contain application keys. They contain no application analytics, advertising scripts or forms. If hosted on GitHub Pages, GitHub processes website requests, including visitor IP addresses, under its own [Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Hosting these documents does not host the financial database or banking callback.

Questions about this application can be directed to the privacy contact above.
