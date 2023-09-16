! ----------------- Desktop https://www.youtube.com -----------------------

www.youtube.com##ytd-reel-shelf-renderer.ytd-item-section-renderer.style-scope
www.youtube.com##ytd-guide-section-renderer.ytd-guide-renderer.style-scope:nth-of-type(3)
www.youtube.com##yt-related-chip-cloud-renderer.ytd-watch-next-secondary-results-renderer.style-scope
www.youtube.com##ytd-item-section-renderer.ytd-watch-next-secondary-results-renderer.style-scope
youtube.com##.ytp-quality-menu .ytp-menuitem:has(.ytp-premium-label)
! YT Menu - Hide the Home button
www.youtube.com###guide [title="Home"], .ytd-mini-guide-entry-renderer[title="Home"]

! YT Homepage - Hide the Shorts section
youtube.com##[is-shorts]
! YT Menu - Hide the Shorts button
www.youtube.com###guide [title="Shorts"], .ytd-mini-guide-entry-renderer[title="Shorts"]
! YT Search - Hide Shorts
www.youtube.com##ytd-search ytd-video-renderer [overlay-style="SHORTS"]:upward(ytd-video-renderer)
! YT Search and Channels - Hide the Shorts sections
www.youtube.com##ytd-reel-shelf-renderer
! YT Channels - Hide the Shorts tab
www.youtube.com##ytd-browse[page-subtype="channels"] [role="tab"]:nth-of-type(3):has-text(Shorts)
! YT Subscriptions - Hide Shorts - Grid View
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-grid-video-renderer [overlay-style="SHORTS"]:upward(ytd-grid-video-renderer)
! YT Subscriptions - Hide Shorts - List View
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-video-renderer [overlay-style="SHORTS"]:upward(ytd-item-section-renderer)
! YT Subscriptions - New Layout - Hide Shorts
www.youtube.com##ytd-browse[page-subtype="subscriptions"] ytd-rich-item-renderer [overlay-style="SHORTS"]:upward(ytd-rich-item-renderer)
! YT Sidebar - Hide Shorts
www.youtube.com###related ytd-compact-video-renderer [overlay-style="SHORTS"]:upward(ytd-compact-video-renderer)


! ----------------- Mobile https://www.m.youtube.com -----------------------
! Hide the Shorts Menu button
m.youtube.com##.pivot-shorts:upward(ytm-pivot-bar-item-renderer)

! Hide Shorts sections
m.youtube.com##ytm-reel-shelf-renderer

! Hide Shorts in search results
m.youtube.com##ytm-search ytm-video-with-context-renderer [data-style="SHORTS"]

m.youtube.com##ytm-pivot-bar-item-renderer:nth-of-type(2)

! Tob Featured Bar
m.youtube.com##.chip-bar-contents

! Suggested Videos
m.youtube.com##ytm-item-section-renderer.single-column-watch-next-modern-panels.scwnr-content:nth-of-type(2)
m.youtube.com##.with-z-index.full-bleed-wn-thumbs.watch-content > .single-column-watch-next-modern-panels.scwnr-content

! Hide videos based on channel URLs
m.youtube.com##ytm-media-item .media-channel a:not([class]):is([href="/@ChannelURL"], [href="/@AnotherChannelURL"]):upward(ytm-media-item)

! Hide Home Tab
m.youtube.com##.pivot-w2w.pivot-bar-item-tab
m.youtube.com##ytm-pivot-bar-item-renderer:nth-of-type(1)

! Hide all videos in home feed containing the phrase "#shorts"
m.youtube.com##ytm-rich-item-renderer:has(#video-title:has-text(#shorts))
m.youtube.com##ytm-rich-item-renderer:has(#video-title:has-text(#Shorts))
m.youtube.com##ytm-rich-item-renderer:has(#video-title:has-text(#short))
m.youtube.com##ytm-rich-item-renderer:has(#video-title:has-text(#Short))

! Hide all videos in subscription feed containing the phrase "#shorts"
m.youtube.com##ytm-item-section-renderer:has(#video-title:has-text(#shorts))
m.youtube.com##ytm-item-section-renderer:has(#video-title:has-text(#Shorts))
m.youtube.com##ytm-item-section-renderer:has(#video-title:has-text(#short))
m.youtube.com##ytm-item-section-renderer:has(#video-title:has-text(#Short))

! Hide shorts button in the bottom navigation bar
m.youtube.com##ytm-pivot-bar-item-renderer:has(.pivot-shorts)

! Hide all videos with the shorts indicator on the thumbnail
m.youtube.com##ytm-video-with-context-renderer:has([data-style="SHORTS"])

! Hide shorts sections
m.youtube.com##ytm-rich-section-renderer:has(ytm-reel-shelf-renderer:has(.reel-shelf-title-wrapper:has-text(Shorts)))
m.youtube.com##ytm-reel-shelf-renderer.item:has(.reel-shelf-title-wrapper:has-text(Shorts))

! Hide shorts tab on channel pages
m.youtube.com##.single-column-browse-results-tabs>a:has-text(Shorts)
m.youtube.com##a.center.single-column-browse-results-tab:nth-of-type(3)
