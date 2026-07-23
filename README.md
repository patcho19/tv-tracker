PAT'S TV TRACKER - PHASE 1

Install/deploy:
1. Extract the ZIP without changing the folder contents.
2. Upload the entire folder to any HTTPS static website host.
3. Open index.html in Chrome or Samsung Internet.
4. Choose Install / Add to Home screen.

Important: service workers and installation do not run correctly from a file:// URL. The app must be served through HTTPS (or localhost for testing).

Data stays on the device. The app migrates the earlier pat-tv-tracker-v1 watchlist and dismissed suggestions when opened in the same browser/site origin.

Build revision: 2.1 - action handling, undo, saved preference restoration and corrupt-storage recovery verified.

PHASE 2 FEATURES
- Explainable recommendation matches and confidence scores
- Mood, pace, commitment and minimum-rating controls
- Pick something for me
- Fair rotation using suggestion impression history
- Tonight mode using available time, mood and source
- Streaming-service preferences and Australian availability search
- Automatic migration from Phase 1 data on the same site origin

Streaming availability is not asserted as live data; the app opens an Australian web availability search because catalogues change.

Revision 3.1: discovery controls persist, selected sorting is honoured, impression rotation is deliberate, Tonight settings persist, and Phase 1 migration carries custom data.

PHASE 3 - DATA RELIABILITY
- Versioned schema migration from Phase 2
- Validated JSON export/import
- Five rolling automatic recovery points
- Pre-import and pre-reset safety snapshots
- Data health, storage use and backup-age indicators
- Safe reset with recovery point
- Manual backups can be saved to OneDrive or another cloud drive

Cloud account sync is not automatic in this static build; it would require sign-in, permissions and a hosted backend/service integration. 
