# Make-Fandom-Useable
Sid's uBlock Origin filters for making Fandom.com useable.  

![image](https://github.com/Welding-Torch/Make-Fandom-Useable/assets/46340124/24505e16-576a-4e24-a8b9-d47d7e7a9f21)  
*https://www.fandom.com/*

This code blocks a lot of the terrible UI elements on Fandom.com, thus making browsing the website a far more pleasureable experience.

### Install Instructions

To add these filters to your Ublock Origin Filters list, perform these 3 easy steps:
1. Click the uBlock extension icon
2. Selecting Dashboard->My filters
3. Copy-paste the below text to your filters list.

```
! I use https://letsblock.it/filters/fandom-cleanup
fandom.com##.global-navigation
fandom.com##.main-container:style(width: 100% !important; margin-left: auto !important; margin-right: auto !important;)
fandom.com##.fandom-community-header__background:style(width: 100% !important)
fandom.com##.fandom-sticky-header:style(left: 0 !important;)
fandom.com##.search-modal::before:style(left: 0 !important;)
fandom.com##body:style(border-left: none !important;)
fandom.com##.notifications-placeholder
fandom.com###WikiaBar
fandom.com##.global-footer
fandom.com###mixed-content-footer
fandom.com##.page__right-rail
fandom.com##.explore-menu.wds-dropdown
fandom.com##.highlight__sticky-container
fandom.com##.search-seeding
fandom.com##.page-side-tool.page-side-edit
fandom.com##.mw-editsection
fandom.com##.reviews

! 2024-04-04 My additions to kill sticky headers and more on fandom.com
fandom.com##.is-visible.fandom-sticky-header
fandom.com##.post-form-wrapper:style(position: static !important)
fandom.com##.feed__wiki-recent-changes--condensed.wiki-recent-changes
fandom.com##.sticky-toc-toggle.page-side-tool
fandom.com##.content-size-toggle.page-side-tool
fandom.com##.global-explore-navigation
```
# About
Fandom (formerly known as Wikia) contains over **45 million pages** of rich text, images, and videos. All this information is difficult to access because of the horrendous UI/UX catastrophe which is Fandom.com. These filters intend to fix that problem by removing all the junk and leaving you with nice, clean pages of information. Like a wiki page should be.

# Before & After
Before Make-Fandom-Useable
![image](https://github.com/user-attachments/assets/eea14454-d30e-4784-ba72-ed4bc6e8edf7)

After Make-Fandom-Useable
![image](https://github.com/user-attachments/assets/2dd4d7bd-26a4-4d98-8e3a-5b8f766ce06c)
