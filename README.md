# Lernressourcentypen (Cluster) im Bildungsportal RLP

This is the repository for publishing the LRT-SKOS vocabulary using GitHub infrastructure (Actions and Pages).

Every time a change is made to a the vocabulary (.ttl) a GitHub-workflow-action is triggered to publish the most recent vocabulary to the `gh-pages`-branch, which is used by GitHub pages.
It spins up a Docker container made from [SkoHub Vocabs](https://github.com/hbz/skohub-vocabs).

## Status

Draft

## CHANGELOG

14.05.2025:

- uses owl:deprecated
- contains some matches to SODIX and WLO



