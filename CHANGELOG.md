# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog].

## Unreleased
### Enhancements
* It is now possible to use the standard Isearch bindings within the
  minibuffer to search the current user input and the minibuffer
  history. Note that this functionality is not compatible with
  Selectrum. See [#41].

[#41]: https://github.com/raxod502/ctrlf/issues/41

## 1.0 (released 2020-03-31)
### Added
* Package `ctrlf`
* Minor mode `ctrlf-mode`
* Faces:
    * `ctrlf-highlight-active`
    * `ctrlf-highlight-passive`
    * `ctrlf-highlight-line`
* Interface user options:
    * `ctrlf-highlight-current-line`
    * `ctrlf-auto-recenter`
    * `ctrlf-show-match-count-at-eol`
    * `ctrlf-mode-bindings`
    * `ctrlf-minibuffer-bindings`
    * `ctrlf-zero-length-match-width`
* Navigation commands:
    * `ctrlf-next-match`
    * `ctrlf-previous-match`
    * `ctrlf-first-match`
    * `ctrlf-last-match`
    * `ctrlf-next-page`
    * `ctrlf-previous-page`
    * `ctrlf-cancel`
* Utility commands:
    * `ctrlf-change-search-style`
    * `ctrlf-toggle-case-fold-search`
    * `ctrlf-recenter-top-bottom`
* Search commands:
    * `ctrlf-forward-literal`
    * `ctrlf-backward-literal`
    * `ctrlf-forward-regexp`
    * `ctrlf-backward-regexp`
    * `ctrlf-forward-fuzzy`
    * `ctrlf-backward-fuzzy`
    * `ctrlf-forward-fuzzy-regexp`
    * `ctrlf-backward-fuzzy-regexp`
* Low-level user options, variables, and functions:
    * `ctrlf-style-alist`
    * `ctrlf-search-history`
    * `ctrlf-forward`
    * `ctrlf-backward`
* Functions for use in configuration:
    * `ctrlf-split-fuzzy`
    * `ctrlf-translate-fuzzy-literal`
    * `ctrlf-translate-fuzzy-regexp`
    * `ctrlf-no-uppercase-literal-p`
    * `ctrlf-no-uppercase-regexp-p`

[keep a changelog]: https://keepachangelog.com/en/1.0.0/
