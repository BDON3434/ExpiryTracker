# Expiry Tracker

## 5 (2026-04-27)

Full Changelog

New Features
Summary Tab: Adds per-character overview showing expired auctions, active auctions, mailbox gold, and next expiry time
Config Tab: New settings panel with controls for alert thresholds, snooze duration, and UI toggles (chat, popup, minimap, addon compartment icon)
Mailbox Gold Tracking: Tracks gold stored in mailbox per character and associates it with expiry timing
Login Alert System:
Chat notification for expired auctions
Popup alert for warning/urgent cases with Snooze, Dismiss, and Open Summary actions
Minimap Button & Addon Compartment Support: Quick access icon with saved position across sessions
Totals Row in Summary: Aggregates expired auctions, active auctions, and total mailbox gold across characters
Enhanced Details Tab: Item tooltips (including battle pets) and shift-click item linking in chat
Persistent UI State: Remembers window positions and popup placement between sessions
Debug Tools: /etrdebug command and Config button for troubleshooting character data
Improvements
Improved readability of item names in Details tab
Cleaner expired/active display formatting (replaces zeros with dashes where appropriate)
Visual highlighting for characters with expired auctions in Summary
Consistent gold expiry coloring based on user-defined thresholds
Improved alert popup UX (scrolling support, pluralization, ESC to close)
Config panel redesigned for usability (scrollable layout)
Summary tab now opens by default

# Expiry Tracker

## [4](https://github.com/plusmouse/ExpiryTracker/tree/4) (2026-01-24)
[Full Changelog](https://github.com/plusmouse/ExpiryTracker/compare/3...4) 

- Bump toc  
-  Better and dynamic representation of expiry times, relative times; some minor stuff #3  
