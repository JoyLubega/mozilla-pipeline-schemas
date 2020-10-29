# Generated Schemas

Summary:

Create the JSON Schema in the templates directory first. Make use of common schema components
from the templates/include directory where possible, including things like the telemetry environment,
clientId, application block, or UUID patterns.

Last month's commit Logs:

* dda5d19d : Add schema for CITP's Pioneer study (#632) by akohlbre
* 7ad71b31 : Add fissionEnabled to new uninstall ping (#631) by Jeff Klukas
* 0f34b318 : Bug 1461690 - Add Uninstall Telemetry ping schema (#629) by Adam Gashlin
* a48ef97e : Bug 1669208 - Add fissionEnabled field to environment by Arkadiusz Komarzewski
* d8899256 : Note special handling of xfocsp-error-report (#630) by Jeff Klukas
* 4d2855dd : Set docker version in CircleCI config (#628) by Will Kahn-Greene
* 14390ddc : Remove edge-validator from CI (#626) by Anthony Miyaguchi.
├── CMakeLists.txt
├── CODE_OF_CONDUCT.md
├── Dockerfile
├── GRAVEYARD.md
├── LICENSE.txt
├── README.md
├── README.pioneer.md
├── README.shield.md
├── mozilla_pipeline_schemas
│   ├── __init__.py
│   ├── bigquery.py
│   ├── cli
│   │   ├── __init__.py
│   │   ├── __main__.py
│   │   └── bigquery.py
│   └── utils.py
├── pom.xml
├── requirements-dev.in
├── requirements-dev.txt
├── requirements.txt
├── schemas
│   ├── activity-stream
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── impression-stats
│   │   │   ├── impression-stats.1.bq
│   │   │   └── impression-stats.1.schema.json
│   │   ├── on-save-recs
│   │   │   ├── on-save-recs.1.bq
│   │   │   └── on-save-recs.1.schema.json
│   │   ├── sessions
│   │   │   ├── sessions.1.bq
│   │   │   └── sessions.1.schema.json
│   │   └── spoc-fills
│   │       ├── spoc-fills.1.bq
│   │       └── spoc-fills.1.schema.json
│   ├── burnham
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── discovery
│   │   │   ├── discovery.1.bq
│   │   │   └── discovery.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── space-ship-ready
│   │   │   ├── space-ship-ready.1.bq
│   │   │   └── space-ship-ready.1.schema.json
│   │   └── starbase46
│   │       ├── starbase46.1.bq
│   │       └── starbase46.1.schema.json
│   ├── coverage
│   │   └── coverage
│   │       ├── coverage.1.bq
│   │       └── coverage.1.schema.json
│   ├── default-browser-agent
│   │   └── default-browser
│   │       ├── default-browser.1.bq
│   │       └── default-browser.1.schema.json
│   ├── edge-validator
│   │   └── error-report
│   │       ├── error-report.1.bq
│   │       └── error-report.1.schema.json
│   ├── eng-workflow
│   │   ├── bmobugs
│   │   │   ├── bmobugs.1.bq
│   │   │   └── bmobugs.1.schema.json
│   │   ├── build
│   │   │   ├── build.1.bq
│   │   │   └── build.1.schema.json
│   │   └── hgpush
│   │       ├── hgpush.1.bq
│   │       └── hgpush.1.schema.json
│   ├── firefox-accounts
│   │   ├── account-ecosystem
│   │   │   ├── account-ecosystem.1.bq
│   │   │   └── account-ecosystem.1.schema.json
│   │   ├── activity-flow-metrics
│   │   │   ├── activity-flow-metrics.1.bq
│   │   │   └── activity-flow-metrics.1.schema.json
│   │   └── amplitude-event
│   │       ├── amplitude-event.1.bq
│   │       └── amplitude-event.1.schema.json
│   ├── firefox-desktop
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── fog-validation
│   │   │   ├── fog-validation.1.bq
│   │   │   └── fog-validation.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── firefox-installer
│   │   └── install
│   │       ├── install.1.bq
│   │       └── install.1.schema.json
│   ├── firefox-launcher-process
│   │   └── launcher-process-failure
│   │       ├── launcher-process-failure.1.bq
│   │       └── launcher-process-failure.1.schema.json
│   ├── glean
│   │   ├── baseline
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   └── events.1.schema.json
│   │   ├── glean
│   │   │   └── glean.1.schema.json
│   │   └── metrics
│   │       └── metrics.1.schema.json
│   ├── glean-js-tmp
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── messaging-system
│   │   ├── cfr
│   │   │   ├── cfr.1.bq
│   │   │   └── cfr.1.schema.json
│   │   ├── moments
│   │   │   ├── moments.1.bq
│   │   │   └── moments.1.schema.json
│   │   ├── onboarding
│   │   │   ├── onboarding.1.bq
│   │   │   └── onboarding.1.schema.json
│   │   ├── personalization-experiment
│   │   │   ├── personalization-experiment.1.bq
│   │   │   └── personalization-experiment.1.schema.json
│   │   ├── snippets
│   │   │   ├── snippets.1.bq
│   │   │   └── snippets.1.schema.json
│   │   ├── undesired-events
│   │   │   ├── undesired-events.1.bq
│   │   │   └── undesired-events.1.schema.json
│   │   └── whats-new-panel
│   │       ├── whats-new-panel.1.bq
│   │       └── whats-new-panel.1.schema.json
│   ├── metadata
│   │   ├── credentials
│   │   │   └── credentials.1.schema.json
│   │   ├── decoded
│   │   │   ├── decoded.1.bq
│   │   │   └── decoded.1.schema.json
│   │   ├── error
│   │   │   ├── error.1.bq
│   │   │   └── error.1.schema.json
│   │   ├── metaschema
│   │   │   └── metaschema.1.schema.json
│   │   ├── pioneer-decoded
│   │   │   ├── pioneer-decoded.1.bq
│   │   │   └── pioneer-decoded.1.schema.json
│   │   ├── pioneer-error
│   │   │   ├── pioneer-error.1.bq
│   │   │   └── pioneer-error.1.schema.json
│   │   ├── pioneer-ingestion
│   │   │   └── pioneer-ingestion.1.schema.json
│   │   ├── raw
│   │   │   ├── raw.1.bq
│   │   │   └── raw.1.schema.json
│   │   ├── sources
│   │   │   └── sources.1.schema.json
│   │   ├── structured-ingestion
│   │   │   └── structured-ingestion.1.schema.json
│   │   └── telemetry-ingestion
│   │       └── telemetry-ingestion.1.schema.json
│   ├── mobile
│   │   └── activation
│   │       ├── activation.1.bq
│   │       └── activation.1.schema.json
│   ├── mozdata
│   │   └── event
│   │       ├── event.1.bq
│   │       └── event.1.schema.json
│   ├── mozilla-lockbox
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── mozilla-mach
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   └── usage
│   │       ├── usage.1.bq
│   │       └── usage.1.schema.json
│   ├── mozphab
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   └── usage
│   │       ├── usage.1.bq
│   │       └── usage.1.schema.json
│   ├── mozza
│   │   └── event
│   │       ├── event.1.bq
│   │       └── event.1.schema.json
│   ├── org-mozilla-connect-firefox
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-fenix
│   │   ├── activation
│   │   │   ├── activation.1.bq
│   │   │   └── activation.1.schema.json
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── first-session
│   │   │   ├── first-session.1.bq
│   │   │   └── first-session.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── migration
│   │   │   ├── migration.1.bq
│   │   │   └── migration.1.schema.json
│   │   ├── startup-timeline
│   │   │   ├── startup-timeline.1.bq
│   │   │   └── startup-timeline.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── org-mozilla-fenix-nightly
│   │   ├── activation
│   │   │   ├── activation.1.bq
│   │   │   └── activation.1.schema.json
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── first-session
│   │   │   ├── first-session.1.bq
│   │   │   └── first-session.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── migration
│   │   │   ├── migration.1.bq
│   │   │   └── migration.1.schema.json
│   │   ├── startup-timeline
│   │   │   ├── startup-timeline.1.bq
│   │   │   └── startup-timeline.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── org-mozilla-fennec-aurora
│   │   ├── activation
│   │   │   ├── activation.1.bq
│   │   │   └── activation.1.schema.json
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── first-session
│   │   │   ├── first-session.1.bq
│   │   │   └── first-session.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── migration
│   │   │   ├── migration.1.bq
│   │   │   └── migration.1.schema.json
│   │   ├── startup-timeline
│   │   │   ├── startup-timeline.1.bq
│   │   │   └── startup-timeline.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── org-mozilla-firefox
│   │   ├── activation
│   │   │   ├── activation.1.bq
│   │   │   └── activation.1.schema.json
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── first-session
│   │   │   ├── first-session.1.bq
│   │   │   └── first-session.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── migration
│   │   │   ├── migration.1.bq
│   │   │   └── migration.1.schema.json
│   │   ├── startup-timeline
│   │   │   ├── startup-timeline.1.bq
│   │   │   └── startup-timeline.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── org-mozilla-firefox-beta
│   │   ├── activation
│   │   │   ├── activation.1.bq
│   │   │   └── activation.1.schema.json
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── first-session
│   │   │   ├── first-session.1.bq
│   │   │   └── first-session.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── migration
│   │   │   ├── migration.1.bq
│   │   │   └── migration.1.schema.json
│   │   ├── startup-timeline
│   │   │   ├── startup-timeline.1.bq
│   │   │   └── startup-timeline.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── org-mozilla-firefoxreality
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── launch
│   │   │   ├── launch.1.bq
│   │   │   └── launch.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-ios-fennec
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-ios-firefox
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-ios-firefoxbeta
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-ios-lockbox
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-mozregression
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   └── usage
│   │       ├── usage.1.bq
│   │       └── usage.1.schema.json
│   ├── org-mozilla-reference-browser
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-tv-firefox
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   └── metrics
│   │       ├── metrics.1.bq
│   │       └── metrics.1.schema.json
│   ├── org-mozilla-vrbrowser
│   │   ├── baseline
│   │   │   ├── baseline.1.bq
│   │   │   └── baseline.1.schema.json
│   │   ├── bookmarks-sync
│   │   │   ├── bookmarks-sync.1.bq
│   │   │   └── bookmarks-sync.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── events
│   │   │   ├── events.1.bq
│   │   │   └── events.1.schema.json
│   │   ├── history-sync
│   │   │   ├── history-sync.1.bq
│   │   │   └── history-sync.1.schema.json
│   │   ├── logins-sync
│   │   │   ├── logins-sync.1.bq
│   │   │   └── logins-sync.1.schema.json
│   │   ├── metrics
│   │   │   ├── metrics.1.bq
│   │   │   └── metrics.1.schema.json
│   │   ├── session-end
│   │   │   ├── session-end.1.bq
│   │   │   └── session-end.1.schema.json
│   │   └── sync
│   │       ├── sync.1.bq
│   │       └── sync.1.schema.json
│   ├── pioneer-citp-news-disinfo
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── measurements
│   │   │   ├── measurements.1.bq
│   │   │   └── measurements.1.schema.json
│   │   └── pioneer-enrollment
│   │       ├── pioneer-enrollment.1.bq
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pioneer-core
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   ├── pioneer-enrollment
│   │   │   ├── pioneer-enrollment.1.bq
│   │   │   └── pioneer-enrollment.1.schema.json
│   │   ├── probes
│   │   │   ├── probes.1.bq
│   │   │   └── probes.1.schema.json
│   │   └── survey
│   │       ├── survey.1.bq
│   │       └── survey.1.schema.json
│   ├── pioneer-debug
│   │   ├── debug
│   │   │   ├── debug.1.bq
│   │   │   └── debug.1.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.1.bq
│   │   │   └── deletion-request.1.schema.json
│   │   └── pioneer-enrollment
│   │       ├── pioneer-enrollment.1.bq
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pioneer-meta
│   │   └── pioneer-enrollment
│   │       ├── pioneer-enrollment.1.bq
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pocket
│   │   └── fire-tv-events
│   │       ├── fire-tv-events.1.bq
│   │       └── fire-tv-events.1.schema.json
│   ├── regrets-reporter
│   │   └── regrets-reporter-update
│   │       ├── regrets-reporter-update.1.bq
│   │       └── regrets-reporter-update.1.schema.json
│   ├── telemetry
│   │   ├── account-ecosystem
│   │   │   ├── account-ecosystem.4.bq
│   │   │   └── account-ecosystem.4.schema.json
│   │   ├── addon-install-blocked
│   │   │   ├── addon-install-blocked.4.bq
│   │   │   └── addon-install-blocked.4.schema.json
│   │   ├── advancedtelemetry
│   │   │   ├── advancedtelemetry.4.bq
│   │   │   └── advancedtelemetry.4.schema.json
│   │   ├── anonymous
│   │   │   ├── anonymous.4.bq
│   │   │   └── anonymous.4.schema.json
│   │   ├── bhr
│   │   │   ├── bhr.4.bq
│   │   │   └── bhr.4.schema.json
│   │   ├── block-autoplay
│   │   │   ├── block-autoplay.1.bq
│   │   │   ├── block-autoplay.1.schema.json
│   │   │   ├── block-autoplay.4.bq
│   │   │   └── block-autoplay.4.schema.json
│   │   ├── certificate-checker
│   │   │   ├── certificate-checker.4.bq
│   │   │   └── certificate-checker.4.schema.json
│   │   ├── core
│   │   │   ├── core.1.bq
│   │   │   ├── core.1.schema.json
│   │   │   ├── core.10.bq
│   │   │   ├── core.10.schema.json
│   │   │   ├── core.2.bq
│   │   │   ├── core.2.schema.json
│   │   │   ├── core.3.bq
│   │   │   ├── core.3.schema.json
│   │   │   ├── core.4.bq
│   │   │   ├── core.4.schema.json
│   │   │   ├── core.5.bq
│   │   │   ├── core.5.schema.json
│   │   │   ├── core.6.bq
│   │   │   ├── core.6.schema.json
│   │   │   ├── core.7.bq
│   │   │   ├── core.7.schema.json
│   │   │   ├── core.8.bq
│   │   │   ├── core.8.schema.json
│   │   │   ├── core.9.bq
│   │   │   └── core.9.schema.json
│   │   ├── crash
│   │   │   ├── crash.2.bq
│   │   │   ├── crash.2.schema.json
│   │   │   ├── crash.4.bq
│   │   │   └── crash.4.schema.json
│   │   ├── deletion
│   │   │   ├── deletion.4.bq
│   │   │   └── deletion.4.schema.json
│   │   ├── deletion-request
│   │   │   ├── deletion-request.4.bq
│   │   │   └── deletion-request.4.schema.json
│   │   ├── deployment-checker
│   │   │   ├── deployment-checker.4.bq
│   │   │   └── deployment-checker.4.schema.json
│   │   ├── disable-sha1rollout
│   │   │   ├── disable-sha1rollout.4.bq
│   │   │   └── disable-sha1rollout.4.schema.json
│   │   ├── dnssec-study-v1
│   │   │   ├── dnssec-study-v1.4.bq
│   │   │   └── dnssec-study-v1.4.schema.json
│   │   ├── downgrade
│   │   │   ├── downgrade.4.bq
│   │   │   └── downgrade.4.schema.json
│   │   ├── event
│   │   │   ├── event.4.bq
│   │   │   └── event.4.schema.json
│   │   ├── first-shutdown
│   │   │   ├── first-shutdown.4.bq
│   │   │   └── first-shutdown.4.schema.json
│   │   ├── flash-shield-study
│   │   │   ├── flash-shield-study.4.bq
│   │   │   └── flash-shield-study.4.schema.json
│   │   ├── focus-event
│   │   │   ├── focus-event.1.bq
│   │   │   └── focus-event.1.schema.json
│   │   ├── frecency-update
│   │   │   ├── frecency-update.1.bq
│   │   │   ├── frecency-update.1.schema.json
│   │   │   ├── frecency-update.4.bq
│   │   │   └── frecency-update.4.schema.json
│   │   ├── ftu
│   │   │   ├── ftu.3.bq
│   │   │   └── ftu.3.schema.json
│   │   ├── health
│   │   │   ├── health.2.bq
│   │   │   ├── health.2.schema.json
│   │   │   ├── health.4.bq
│   │   │   ├── health.4.schema.json
│   │   │   ├── health.9.bq
│   │   │   └── health.9.schema.json
│   │   ├── heartbeat
│   │   │   ├── heartbeat.4.bq
│   │   │   └── heartbeat.4.schema.json
│   │   ├── installation
│   │   │   ├── installation.1.bq
│   │   │   └── installation.1.schema.json
│   │   ├── main
│   │   │   ├── main.4.bq
│   │   │   └── main.4.schema.json
│   │   ├── malware-addon-states
│   │   │   ├── malware-addon-states.4.bq
│   │   │   └── malware-addon-states.4.schema.json
│   │   ├── mobile-event
│   │   │   ├── mobile-event.1.bq
│   │   │   └── mobile-event.1.schema.json
│   │   ├── mobile-metrics
│   │   │   ├── mobile-metrics.1.bq
│   │   │   └── mobile-metrics.1.schema.json
│   │   ├── modules
│   │   │   ├── modules.4.bq
│   │   │   └── modules.4.schema.json
│   │   ├── new-profile
│   │   │   ├── new-profile.4.bq
│   │   │   └── new-profile.4.schema.json
│   │   ├── normandy-login-study
│   │   │   ├── normandy-login-study.4.bq
│   │   │   └── normandy-login-study.4.schema.json
│   │   ├── optout
│   │   │   ├── optout.4.bq
│   │   │   └── optout.4.schema.json
│   │   ├── outofdate-notifications-system-addon
│   │   │   ├── outofdate-notifications-system-addon.4.bq
│   │   │   └── outofdate-notifications-system-addon.4.schema.json
│   │   ├── pioneer-study
│   │   │   ├── pioneer-study.4.bq
│   │   │   └── pioneer-study.4.schema.json
│   │   ├── pre-account
│   │   │   ├── pre-account.4.bq
│   │   │   └── pre-account.4.schema.json
│   │   ├── prio
│   │   │   ├── prio.4.bq
│   │   │   └── prio.4.schema.json
│   │   ├── regrets-reporter-update
│   │   │   ├── regrets-reporter-update.4.bq
│   │   │   └── regrets-reporter-update.4.schema.json
│   │   ├── saved-session
│   │   │   ├── saved-session.4.bq
│   │   │   └── saved-session.4.schema.json
│   │   ├── searchvol
│   │   │   ├── searchvol.4.bq
│   │   │   └── searchvol.4.schema.json
│   │   ├── searchvolextra
│   │   │   ├── searchvolextra.4.bq
│   │   │   └── searchvolextra.4.schema.json
│   │   ├── shield-icq-v1
│   │   │   ├── shield-icq-v1.4.bq
│   │   │   └── shield-icq-v1.4.schema.json
│   │   ├── shield-study
│   │   │   ├── shield-study.3.bq
│   │   │   ├── shield-study.3.schema.json
│   │   │   ├── shield-study.4.bq
│   │   │   └── shield-study.4.schema.json
│   │   ├── shield-study-addon
│   │   │   ├── shield-study-addon.3.bq
│   │   │   ├── shield-study-addon.3.schema.json
│   │   │   ├── shield-study-addon.4.bq
│   │   │   └── shield-study-addon.4.schema.json
│   │   ├── shield-study-error
│   │   │   ├── shield-study-error.3.bq
│   │   │   ├── shield-study-error.3.schema.json
│   │   │   ├── shield-study-error.4.bq
│   │   │   └── shield-study-error.4.schema.json
│   │   ├── sync
│   │   │   ├── sync.4.bq
│   │   │   ├── sync.4.schema.json
│   │   │   ├── sync.5.bq
│   │   │   └── sync.5.schema.json
│   │   ├── system-addon-deployment-diagnostics
│   │   │   ├── system-addon-deployment-diagnostics.4.bq
│   │   │   └── system-addon-deployment-diagnostics.4.schema.json
│   │   ├── testpilot
│   │   │   ├── testpilot.4.bq
│   │   │   └── testpilot.4.schema.json
│   │   ├── testpilottest
│   │   │   ├── testpilottest.4.bq
│   │   │   └── testpilottest.4.schema.json
│   │   ├── third-party-modules
│   │   │   ├── third-party-modules.4.bq
│   │   │   └── third-party-modules.4.schema.json
│   │   ├── tls-13-study
│   │   │   ├── tls-13-study.4.bq
│   │   │   └── tls-13-study.4.schema.json
│   │   ├── tls-13-study-v1
│   │   │   ├── tls-13-study-v1.4.bq
│   │   │   └── tls-13-study-v1.4.schema.json
│   │   ├── tls-13-study-v2
│   │   │   ├── tls-13-study-v2.4.bq
│   │   │   └── tls-13-study-v2.4.schema.json
│   │   ├── tls-13-study-v3
│   │   │   ├── tls-13-study-v3.4.bq
│   │   │   └── tls-13-study-v3.4.schema.json
│   │   ├── tls-13-study-v4
│   │   │   ├── tls-13-study-v4.4.bq
│   │   │   └── tls-13-study-v4.4.schema.json
│   │   ├── tls13-middlebox-alt-server-hello-1
│   │   │   ├── tls13-middlebox-alt-server-hello-1.4.bq
│   │   │   └── tls13-middlebox-alt-server-hello-1.4.schema.json
│   │   ├── tls13-middlebox-beta
│   │   │   ├── tls13-middlebox-beta.4.bq
│   │   │   └── tls13-middlebox-beta.4.schema.json
│   │   ├── tls13-middlebox-draft22
│   │   │   ├── tls13-middlebox-draft22.4.bq
│   │   │   └── tls13-middlebox-draft22.4.schema.json
│   │   ├── tls13-middlebox-ghack
│   │   │   ├── tls13-middlebox-ghack.4.bq
│   │   │   └── tls13-middlebox-ghack.4.schema.json
│   │   ├── tls13-middlebox-repetition
│   │   │   ├── tls13-middlebox-repetition.4.bq
│   │   │   └── tls13-middlebox-repetition.4.schema.json
│   │   ├── tls13-middlebox-testing
│   │   │   ├── tls13-middlebox-testing.4.bq
│   │   │   └── tls13-middlebox-testing.4.schema.json
│   │   ├── uitour-tag
│   │   │   ├── uitour-tag.4.bq
│   │   │   └── uitour-tag.4.schema.json
│   │   ├── uninstall
│   │   │   ├── uninstall.4.bq
│   │   │   └── uninstall.4.schema.json
│   │   ├── untrusted-modules
│   │   │   ├── untrusted-modules.4.bq
│   │   │   └── untrusted-modules.4.schema.json
│   │   ├── update
│   │   │   ├── update.4.bq
│   │   │   └── update.4.schema.json
│   │   ├── voice
│   │   │   ├── voice.4.bq
│   │   │   └── voice.4.schema.json
│   │   ├── voice-feedback
│   │   │   ├── voice-feedback.4.bq
│   │   │   └── voice-feedback.4.schema.json
│   │   ├── x-contextual-feature-recommendation
│   │   │   ├── x-contextual-feature-recommendation.4.bq
│   │   │   └── x-contextual-feature-recommendation.4.schema.json
│   │   └── xfocsp-error-report
│   │       ├── xfocsp-error-report.4.bq
│   │       └── xfocsp-error-report.4.schema.json
│   ├── webpagetest
│   │   └── webpagetest-run
│   │       ├── webpagetest-run.1.bq
│   │       └── webpagetest-run.1.schema.json
│   └── xfocsp-error-report
│       └── xfocsp-error-report
│           ├── xfocsp-error-report.4.bq
│           └── xfocsp-error-report.4.schema.json
├── scripts
│   ├── assert-consistent-schemas
│   ├── assert-telemetry-version
│   ├── extract_crash_annotation_fields
│   ├── extract_glean_client_info_descriptions
│   ├── extract_probe_dictionary_descriptions
│   ├── inject-metadata
│   ├── mps-build
│   ├── mps-shell
│   ├── mps-test
│   └── test-pytest-generation
├── setup.py
├── templates
│   ├── activity-stream
│   │   ├── defaults.schema.json
│   │   ├── events
│   │   │   └── events.1.schema.json
│   │   ├── impression-stats
│   │   │   └── impression-stats.1.schema.json
│   │   ├── on-save-recs
│   │   │   └── on-save-recs.1.schema.json
│   │   ├── sessions
│   │   │   └── sessions.1.schema.json
│   │   └── spoc-fills
│   │       └── spoc-fills.1.schema.json
│   ├── coverage
│   │   └── coverage
│   │       └── coverage.1.schema.json
│   ├── default-browser-agent
│   │   └── default-browser
│   │       └── default-browser.1.schema.json
│   ├── edge-validator
│   │   └── error-report
│   │       └── error-report.1.schema.json
│   ├── eng-workflow
│   │   ├── bmobugs
│   │   │   └── bmobugs.1.schema.json
│   │   ├── build
│   │   │   └── build.1.schema.json
│   │   └── hgpush
│   │       └── hgpush.1.schema.json
│   ├── firefox-accounts
│   │   ├── account-ecosystem
│   │   │   └── account-ecosystem.1.schema.json
│   │   ├── activity-flow-metrics
│   │   │   └── activity-flow-metrics.1.schema.json
│   │   └── amplitude-event
│   │       └── amplitude-event.1.schema.json
│   ├── firefox-installer
│   │   └── install
│   │       └── install.1.schema.json
│   ├── firefox-launcher-process
│   │   └── launcher-process-failure
│   │       └── launcher-process-failure.1.schema.json
│   ├── glean
│   │   ├── defaults.schema.json
│   │   └── glean
│   │       └── glean.1.schema.json
│   ├── include
│   │   ├── account-ecosystem
│   │   │   └── ecosystem_user_id_type.1.schema.json
│   │   ├── activity-stream
│   │   │   ├── experiments.1.schema.json
│   │   │   ├── impressionId.1.schema.json
│   │   │   ├── page.1.schema.json
│   │   │   └── sessionId.1.schema.json
│   │   ├── common
│   │   │   ├── event.1.schema.json
│   │   │   ├── pattern_uuid.1.schema.json
│   │   │   ├── placeholder.1.schema.json
│   │   │   └── snakecase.1.schema.json
│   │   ├── glean
│   │   │   ├── CHANGELOG.md
│   │   │   ├── base_object.1.schema.json
│   │   │   ├── boolean.1.schema.json
│   │   │   ├── client_info.1.schema.json
│   │   │   ├── counter.1.schema.json
│   │   │   ├── custom_distribution.1.schema.json
│   │   │   ├── datetime.1.schema.json
│   │   │   ├── dot_separated_short_id.1.schema.json
│   │   │   ├── enumeration.1.schema.json
│   │   │   ├── event.1.schema.json
│   │   │   ├── glean.1.schema.json
│   │   │   ├── histogram.1.schema.json
│   │   │   ├── jwe.1.schema.json
│   │   │   ├── labeled_group.1.schema.json
│   │   │   ├── memory_distribution.1.schema.json
│   │   │   ├── number.1.schema.json
│   │   │   ├── quantity.1.schema.json
│   │   │   ├── rate.1.schema.json
│   │   │   ├── short_id.1.schema.json
│   │   │   ├── string.1.schema.json
│   │   │   ├── string_list.1.schema.json
│   │   │   ├── time_unit.1.schema.json
│   │   │   ├── timespan.1.schema.json
│   │   │   ├── timing_distribution.1.schema.json
│   │   │   ├── usage.1.schema.json
│   │   │   ├── use_counter.1.schema.json
│   │   │   └── uuid.1.schema.json
│   │   ├── metadata
│   │   │   ├── CHANGELOG.md
│   │   │   ├── additionalProperties.1.schema.json
│   │   │   ├── decoded.1.schema.json
│   │   │   ├── error.1.schema.json
│   │   │   ├── ingestionCommonMetadata.1.schema.json
│   │   │   ├── ingestionTopLevel.1.schema.json
│   │   │   ├── pioneerTopLevel.1.schema.json
│   │   │   ├── raw.1.schema.json
│   │   │   └── uri.1.schema.json
│   │   ├── pioneer-study
│   │   │   ├── deletion-request.1.schema.json
│   │   │   ├── metadata.1.parquetmr.txt
│   │   │   └── pioneer-enrollment.1.schema.json
│   │   ├── regrets-reporter
│   │   │   ├── amountsByCategory.1.schema.json
│   │   │   ├── dataDeletionRequest.1.schema.json
│   │   │   ├── regretReport.1.schema.json
│   │   │   ├── regretReportData.1.schema.json
│   │   │   ├── regretsReporterUpdate.1.schema.json
│   │   │   ├── sharedDataEventMetadata.1.schema.json
│   │   │   ├── videoMetadata.1.schema.json
│   │   │   ├── youTubeNavigationMetadata.1.schema.json
│   │   │   ├── youTubeNavigationUrlType.1.schema.json
│   │   │   ├── youTubePageEntryPoint.1.schema.json
│   │   │   └── youTubeUsageStatisticsUpdate.1.schema.json
│   │   └── telemetry
│   │       ├── addon.1.schema.json
│   │       ├── application.1.schema.json
│   │       ├── buildId.1.schema.json
│   │       ├── clientId.1.schema.json
│   │       ├── coreCommon.1.schema.json
│   │       ├── coreCommon.2.schema.json
│   │       ├── creationDate.1.schema.json
│   │       ├── environment.1.schema.json
│   │       ├── environmentAccountEcosystem.1.schema.json
│   │       ├── gc.1.schema.json
│   │       ├── gcItem.1.schema.json
│   │       ├── hexAddress.1.schema.json
│   │       ├── histogram.1.schema.json
│   │       ├── id.1.schema.json
│   │       ├── mainPayload.1.schema.json
│   │       ├── mainSchemaId.1.schema.json
│   │       ├── metricsData.1.schema.json
│   │       ├── mobileCommon.1.schema.json
│   │       ├── mobileEvent.1.schema.json
│   │       ├── processData.1.schema.json
│   │       ├── scalars.1.schema.json
│   │       ├── shieldStudyAddonPayload.3.parquetmr.txt
│   │       ├── shieldStudyAddonPayload.3.schema.json
│   │       ├── shieldStudyErrorPayload.3.parquetmr.txt
│   │       ├── shieldStudyErrorPayload.3.schema.json
│   │       ├── shieldStudyPayload.3.parquetmr.txt
│   │       ├── shieldStudyPayload.3.schema.json
│   │       ├── syncError.1.schema.json
│   │       ├── syncItem.1.schema.json
│   │       ├── syncMigration.1.schema.json
│   │       ├── syncNamedCount.1.schema.json
│   │       └── syncPayload.1.schema.json
│   ├── messaging-system
│   │   ├── cfr
│   │   │   └── cfr.1.schema.json
│   │   ├── defaults.schema.json
│   │   ├── moments
│   │   │   └── moments.1.schema.json
│   │   ├── onboarding
│   │   │   └── onboarding.1.schema.json
│   │   ├── personalization-experiment
│   │   │   └── personalization-experiment.1.schema.json
│   │   ├── snippets
│   │   │   └── snippets.1.schema.json
│   │   ├── undesired-events
│   │   │   └── undesired-events.1.schema.json
│   │   └── whats-new-panel
│   │       └── whats-new-panel.1.schema.json
│   ├── metadata
│   │   ├── README.md
│   │   ├── credentials
│   │   │   └── credentials.1.schema.json
│   │   ├── decoded
│   │   │   └── decoded.1.schema.json
│   │   ├── defaults.schema.json
│   │   ├── error
│   │   │   └── error.1.schema.json
│   │   ├── metaschema
│   │   │   └── metaschema.1.schema.json
│   │   ├── pioneer-decoded
│   │   │   └── pioneer-decoded.1.schema.json
│   │   ├── pioneer-error
│   │   │   └── pioneer-error.1.schema.json
│   │   ├── pioneer-ingestion
│   │   │   └── pioneer-ingestion.1.schema.json
│   │   ├── raw
│   │   │   └── raw.1.schema.json
│   │   ├── sources
│   │   │   └── sources.1.schema.json
│   │   ├── structured-ingestion
│   │   │   └── structured-ingestion.1.schema.json
│   │   └── telemetry-ingestion
│   │       └── telemetry-ingestion.1.schema.json
│   ├── mobile
│   │   └── activation
│   │       └── activation.1.schema.json
│   ├── mozdata
│   │   └── event
│   │       └── event.1.schema.json
│   ├── mozza
│   │   └── event
│   │       └── event.1.schema.json
│   ├── pioneer-citp-news-disinfo
│   │   ├── defaults.schema.json
│   │   ├── deletion-request
│   │   │   └── deletion-request.1.schema.json
│   │   ├── measurements
│   │   │   └── measurements.1.schema.json
│   │   └── pioneer-enrollment
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pioneer-core
│   │   ├── defaults.schema.json
│   │   ├── deletion-request
│   │   │   └── deletion-request.1.schema.json
│   │   ├── pioneer-enrollment
│   │   │   └── pioneer-enrollment.1.schema.json
│   │   ├── probes
│   │   │   └── probes.1.schema.json
│   │   └── survey
│   │       └── survey.1.schema.json
│   ├── pioneer-debug
│   │   ├── debug
│   │   │   └── debug.1.schema.json
│   │   ├── defaults.schema.json
│   │   ├── deletion-request
│   │   │   └── deletion-request.1.schema.json
│   │   └── pioneer-enrollment
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pioneer-meta
│   │   ├── defaults.schema.json
│   │   └── pioneer-enrollment
│   │       └── pioneer-enrollment.1.schema.json
│   ├── pocket
│   │   └── fire-tv-events
│   │       └── fire-tv-events.1.schema.json
│   ├── regrets-reporter
│   │   └── regrets-reporter-update
│   │       └── regrets-reporter-update.1.schema.json
│   ├── telemetry
│   │   ├── account-ecosystem
│   │   │   └── account-ecosystem.4.schema.json
│   │   ├── addon-install-blocked
│   │   │   └── addon-install-blocked.4.schema.json
│   │   ├── advancedtelemetry
│   │   │   └── advancedtelemetry.4.schema.json
│   │   ├── anonymous
│   │   │   └── anonymous.4.schema.json
│   │   ├── bhr
│   │   │   └── bhr.4.schema.json
│   │   ├── block-autoplay
│   │   │   ├── block-autoplay.1.schema.json
│   │   │   └── block-autoplay.4.schema.json
│   │   ├── certificate-checker
│   │   │   └── certificate-checker.4.schema.json
│   │   ├── core
│   │   │   ├── core.1.schema.json
│   │   │   ├── core.10.schema.json
│   │   │   ├── core.2.schema.json
│   │   │   ├── core.3.schema.json
│   │   │   ├── core.4.schema.json
│   │   │   ├── core.5.schema.json
│   │   │   ├── core.6.schema.json
│   │   │   ├── core.7.schema.json
│   │   │   ├── core.8.schema.json
│   │   │   └── core.9.schema.json
│   │   ├── crash
│   │   │   ├── crash.2.schema.json
│   │   │   └── crash.4.schema.json
│   │   ├── defaults.schema.json
│   │   ├── deletion
│   │   │   └── deletion.4.schema.json
│   │   ├── deletion-request
│   │   │   └── deletion-request.4.schema.json
│   │   ├── deployment-checker
│   │   │   └── deployment-checker.4.schema.json
│   │   ├── disable-sha1rollout
│   │   │   └── disable-sha1rollout.4.schema.json
│   │   ├── disableSHA1rollout
│   │   │   └── README.md
│   │   ├── dnssec-study-v1
│   │   │   └── dnssec-study-v1.4.schema.json
│   │   ├── downgrade
│   │   │   └── downgrade.4.schema.json
│   │   ├── event
│   │   │   └── event.4.schema.json
│   │   ├── first-shutdown
│   │   │   └── first-shutdown.4.schema.json
│   │   ├── flash-shield-study
│   │   │   └── flash-shield-study.4.schema.json
│   │   ├── focus-event
│   │   │   └── focus-event.1.schema.json
│   │   ├── frecency-update
│   │   │   ├── frecency-update.1.schema.json
│   │   │   └── frecency-update.4.schema.json
│   │   ├── ftu
│   │   │   └── ftu.3.schema.json
│   │   ├── health
│   │   │   ├── health.2.schema.json
│   │   │   ├── health.4.schema.json
│   │   │   └── health.9.schema.json
│   │   ├── heartbeat
│   │   │   └── heartbeat.4.schema.json
│   │   ├── installation
│   │   │   └── installation.1.schema.json
│   │   ├── main
│   │   │   └── main.4.schema.json
│   │   ├── malware-addon-states
│   │   │   └── malware-addon-states.4.schema.json
│   │   ├── mobile-event
│   │   │   └── mobile-event.1.schema.json
│   │   ├── mobile-metrics
│   │   │   └── mobile-metrics.1.schema.json
│   │   ├── modules
│   │   │   └── modules.4.schema.json
│   │   ├── new-profile
│   │   │   └── new-profile.4.schema.json
│   │   ├── normandy-login-study
│   │   │   └── normandy-login-study.4.schema.json
│   │   ├── optout
│   │   │   └── optout.4.schema.json
│   │   ├── outofdate-notifications-system-addon
│   │   │   └── outofdate-notifications-system-addon.4.schema.json
│   │   ├── pioneer-study
│   │   │   └── pioneer-study.4.schema.json
│   │   ├── pre-account
│   │   │   └── pre-account.4.schema.json
│   │   ├── prio
│   │   │   └── prio.4.schema.json
│   │   ├── regrets-reporter-update
│   │   │   └── regrets-reporter-update.4.schema.json
│   │   ├── saved-session
│   │   │   └── saved-session.4.schema.json
│   │   ├── searchvol
│   │   │   └── searchvol.4.schema.json
│   │   ├── searchvolextra
│   │   │   └── searchvolextra.4.schema.json
│   │   ├── shield-icq-v1
│   │   │   └── shield-icq-v1.4.schema.json
│   │   ├── shield-study
│   │   │   ├── shield-study.3.parquetmr.txt
│   │   │   ├── shield-study.3.schema.json
│   │   │   └── shield-study.4.schema.json
│   │   ├── shield-study-addon
│   │   │   ├── shield-study-addon.3.parquetmr.txt
│   │   │   ├── shield-study-addon.3.schema.json
│   │   │   └── shield-study-addon.4.schema.json
│   │   ├── shield-study-error
│   │   │   ├── shield-study-error.3.parquetmr.txt
│   │   │   ├── shield-study-error.3.schema.json
│   │   │   └── shield-study-error.4.schema.json
│   │   ├── sync
│   │   │   ├── sync.4.schema.json
│   │   │   └── sync.5.schema.json
│   │   ├── system-addon-deployment-diagnostics
│   │   │   └── system-addon-deployment-diagnostics.4.schema.json
│   │   ├── testpilot
│   │   │   └── testpilot.4.schema.json
│   │   ├── testpilottest
│   │   │   └── testpilottest.4.schema.json
│   │   ├── third-party-modules
│   │   │   └── third-party-modules.4.schema.json
│   │   ├── tls-13-study
│   │   │   └── tls-13-study.4.schema.json
│   │   ├── tls-13-study-v1
│   │   │   └── tls-13-study-v1.4.schema.json
│   │   ├── tls-13-study-v2
│   │   │   └── tls-13-study-v2.4.schema.json
│   │   ├── tls-13-study-v3
│   │   │   └── tls-13-study-v3.4.schema.json
│   │   ├── tls-13-study-v4
│   │   │   └── tls-13-study-v4.4.schema.json
│   │   ├── tls13-middlebox-alt-server-hello-1
│   │   │   └── tls13-middlebox-alt-server-hello-1.4.schema.json
│   │   ├── tls13-middlebox-beta
│   │   │   └── tls13-middlebox-beta.4.schema.json
│   │   ├── tls13-middlebox-draft22
│   │   │   └── tls13-middlebox-draft22.4.schema.json
│   │   ├── tls13-middlebox-ghack
│   │   │   └── tls13-middlebox-ghack.4.schema.json
│   │   ├── tls13-middlebox-repetition
│   │   │   └── tls13-middlebox-repetition.4.schema.json
│   │   ├── tls13-middlebox-testing
│   │   │   └── tls13-middlebox-testing.4.schema.json
│   │   ├── uitour-tag
│   │   │   └── uitour-tag.4.schema.json
│   │   ├── uninstall
│   │   │   └── uninstall.4.schema.json
│   │   ├── untrusted-modules
│   │   │   └── untrusted-modules.4.schema.json
│   │   ├── untrustedModules
│   │   │   └── README.md
│   │   ├── update
│   │   │   └── update.4.schema.json
│   │   ├── voice
│   │   │   └── voice.4.schema.json
│   │   ├── voice-feedback
│   │   │   └── voice-feedback.4.schema.json
│   │   ├── x-contextual-feature-recommendation
│   │   │   └── x-contextual-feature-recommendation.4.schema.json
│   │   └── xfocsp-error-report
│   │       └── xfocsp-error-report.4.schema.json
│   ├── webpagetest
│   │   └── webpagetest-run
│   │       └── webpagetest-run.1.schema.json
│   └── xfocsp-error-report
│       └── xfocsp-error-report
│           └── xfocsp-error-report.4.schema.json
├── tests
│   ├── conftest.py
│   ├── test_duplicate_schemas.py
│   ├── test_mps_bigquery.py
│   ├── test_mps_cli_bigquery.py
│   ├── test_mps_utils.py
│   ├── test_pipeline_metadata.py
│   ├── test_schema_structure.py
│   ├── test_telemetry_version.py
│   ├── test_validation_java.py
│   ├── test_validation_python.py
│   └── utils.py
└── validation
    ├── activity-stream
    │   ├── events.1.alternative.pass.json
    │   ├── events.1.as-cn.pass.json
    │   ├── events.1.browser_session_id.pass.json
    │   ├── events.1.experiments.pass.json
    │   ├── events.1.sample.pass.json
    │   ├── impression-stats.1.as-cn.pass.json
    │   ├── impression-stats.1.experiments.pass.json
    │   ├── impression-stats.1.loadedContent.pass.json
    │   ├── impression-stats.1.sample.pass.json
    │   ├── impression-stats.1.save-to-pocket.pass.json
    │   ├── on-save-recs.1.sample.pass.json
    │   ├── sessions.1.sample.pass.json
    │   └── spoc-fills.1.sample.pass.json
    ├── coverage
    │   ├── coverage.1.extra_field.fail.json
    │   ├── coverage.1.missing_field.fail.json
    │   └── coverage.1.sample.pass.json
    ├── default-browser-agent
    │   ├── default-browser.1.sample.pass.json
    │   └── default-browser.1.sample_all_fields.pass.json
    ├── edge-validator
    │   ├── error-report.1.missing-error.fail.json
    │   ├── error-report.1.negative-error.fail.json
    │   ├── error-report.1.over-100-error.fail.json
    │   └── error-report.1.sample.pass.json
    ├── eng-workflow
    │   ├── bmobugs.1.flags.pass.json
    │   ├── bmobugs.1.newer.pass.json
    │   ├── bmobugs.1.oldone.pass.json
    │   ├── build.1.buildAttrs.pass.json
    │   ├── build.1.sample.pass.json
    │   ├── hgpush.1.diffstat_null.pass.json
    │   ├── hgpush.1.landingSystem_null.pass.json
    │   └── hgpush.1.sample.pass.json
    ├── firefox-accounts
    │   ├── account-ecosystem.1.no_ids.fail.json
    │   ├── account-ecosystem.1.sample.pass.json
    │   ├── account-ecosystem.1.user_id_only.pass.json
    │   ├── activity-flow-metrics.1.sample.pass.json
    │   ├── amplitude-event.1.fxa-auth-server--fxa_login--success.pass.json
    │   ├── amplitude-event.1.fxa-content-server--fxa_reg--view.pass.json
    │   └── amplitude-event.1.fxa-payments-server--fxa_pay_setup--engage.pass.json
    ├── firefox-installer
    │   ├── install.1.full.pass.json
    │   └── install.1.stub.pass.json
    ├── firefox-launcher-process
    │   └── launcher-process-failure.1.sample.pass.json
    ├── glean
    │   ├── glean.1.activation.pass.json
    │   ├── glean.1.baseline.pass.json
    │   ├── glean.1.bookmarks-sync.pass.json
    │   ├── glean.1.events.pass.json
    │   ├── glean.1.history-sync.pass.json
    │   ├── glean.1.invalid_timing_distribution.fail.json
    │   ├── glean.1.invalid_use_counter.fail.json
    │   ├── glean.1.locale.pass.json
    │   ├── glean.1.metrics.pass.json
    │   └── glean.1.null_timestamp.fail.json
    ├── messaging-system
    │   ├── cfr.1.both_ids.fail.json
    │   ├── cfr.1.experiments.pass.json
    │   ├── cfr.1.prerelease.pass.json
    │   ├── cfr.1.release.pass.json
    │   ├── moments.1.prerelease.pass.json
    │   ├── moments.1.release.pass.json
    │   ├── onboarding.1.browser_session_id.pass.json
    │   ├── onboarding.1.event.pass.json
    │   ├── onboarding.1.experiments.pass.json
    │   ├── personalization-experiment.1.event.pass.json
    │   ├── snippets.1.event.pass.json
    │   ├── undesired-events.1.event.pass.json
    │   └── whats-new-panel.1.event.pass.json
    ├── metadata
    │   ├── credentials.1.sample.pass.json
    │   ├── pioneer-ingestion.1.sample.pass.json
    │   ├── sources.1.sample.pass.json
    │   └── structured-ingestion.1.sample.pass.json
    ├── mobile
    │   ├── activation.1.both_ids.fail.json
    │   └── activation.1.sample.pass.json
    ├── mozza
    │   └── event.1.sample.pass.json
    ├── pioneer-citp-news-disinfo
    │   └── measurements.1.sample.pass.json
    ├── pioneer-debug
    │   ├── debug.1.sample.pass.json
    │   ├── deletion-request.1.additional-properties.pass.json
    │   └── deletion-request.1.sample.pass.json
    ├── pocket
    │   └── fire-tv-events.1.sample.pass.json
    ├── regrets-reporter
    │   ├── regrets-reporter-update.1.data-deletion-request.pass.json
    │   ├── regrets-reporter-update.1.regret-report-step-1.pass.json
    │   ├── regrets-reporter-update.1.regret-report-step-2.pass.json
    │   └── regrets-reporter-update.1.usage-statistics-update.pass.json
    ├── telemetry
    │   ├── account-ecosystem.4.sample.pass.json
    │   ├── anonymous.4.sample.pass.json
    │   ├── block-autoplay.1.counters.pass.json
    │   ├── block-autoplay.1.prompt.pass.json
    │   ├── block-autoplay.1.settings.pass.json
    │   ├── core.10.enhancedSearch.pass.json
    │   ├── core.10.fennec.pass.json
    │   ├── core.10.one_digit_displayversion.pass.json
    │   ├── core.10.sample.pass.json
    │   ├── core.9.displayversion.fail.json
    │   ├── core.9.sample.pass.json
    │   ├── crash.4.null_minidumphashsha256.pass.json
    │   ├── crash.4.null_stackTraces.pass.json
    │   ├── crash.4.null_vendor.pass.json
    │   ├── crash.4.sample.pass.json
    │   ├── crash.4.stackTraces.pass.json
    │   ├── deletion-request.4.noclientid.fail.json
    │   ├── deletion-request.4.payload.pass.json
    │   ├── deletion-request.4.sample.pass.json
    │   ├── dnssec-study-v1.4.dnsresponses.pass.json
    │   ├── dnssec-study-v1.4.error.pass.json
    │   ├── downgrade.4.sample.pass.json
    │   ├── event.4.sample.pass.json
    │   ├── focus-event.1.error.pass.json
    │   ├── focus-event.1.sample.pass.json
    │   ├── frecency-update.4.sample.pass.json
    │   ├── health.4.sample.pass.json
    │   ├── heartbeat.4.sample.fail.json
    │   ├── heartbeat.4.sample.pass.json
    │   ├── installation.1.sample.pass.json
    │   ├── main.4.GMPlugins.fail.json
    │   ├── main.4.activeplugins.fail.json
    │   ├── main.4.adapter.fail.json
    │   ├── main.4.adapter_null_gpuactive.pass.json
    │   ├── main.4.addon.fail.json
    │   ├── main.4.attribution.pass.json
    │   ├── main.4.device.fail.json
    │   ├── main.4.displayversion.fail.json
    │   ├── main.4.empty.fail.json
    │   ├── main.4.experiments.fail.json
    │   ├── main.4.features.fail.json
    │   ├── main.4.gc_sample.pass.json
    │   ├── main.4.gc_sample_2.pass.json
    │   ├── main.4.good_histogram.pass.json
    │   ├── main.4.hdd_type.fail.json
    │   ├── main.4.hdd_type.pass.json
    │   ├── main.4.hdd_type_empty.fail.json
    │   ├── main.4.hdd_type_null.pass.json
    │   ├── main.4.headless.fail.json
    │   ├── main.4.headless.pass.json
    │   ├── main.4.histogram.fail.json
    │   ├── main.4.intl_alldata.pass.json
    │   ├── main.4.intl_nosection.pass.json
    │   ├── main.4.intl_null.fail.json
    │   ├── main.4.intl_null.pass.json
    │   ├── main.4.latewrites.fail.json
    │   ├── main.4.latewrites.pass.json
    │   ├── main.4.min.pass.json
    │   ├── main.4.monitors.fail.json
    │   ├── main.4.negative_count.fail.json
    │   ├── main.4.privatesearchengine.fail.json
    │   ├── main.4.privatesearchenginedataloadpath.fail.json
    │   ├── main.4.privatesearchenginedataname.fail.json
    │   ├── main.4.privatesearchenginedataorigin.fail.json
    │   ├── main.4.privatesearchenginedataurl.fail.json
    │   ├── main.4.profile.pass.json
    │   ├── main.4.sample.pass.json
    │   ├── main.4.sec.fail.json
    │   ├── main.4.services.pass.json
    │   ├── main.4.slow_sql.fail.json
    │   ├── mobile-event.1.error.pass.json
    │   ├── mobile-event.1.sample.pass.json
    │   ├── mobile-metrics.1.sample.pass.json
    │   ├── modules.4.linux.pass.json
    │   ├── modules.4.mac.pass.json
    │   ├── modules.4.windows.pass.json
    │   ├── new-profile.4.sample.pass.json
    │   ├── normandy-login-study.4.sample.pass.json
    │   ├── optout.4.clientid.fail.json
    │   ├── optout.4.payload.fail.json
    │   ├── optout.4.sample.pass.json
    │   ├── pioneer-study.4.deletion-request.pass.json
    │   ├── pioneer-study.4.enrollment-request.pass.json
    │   ├── pioneer-study.4.sample-v1.fail.json
    │   ├── pioneer-study.4.sample.pass.json
    │   ├── pre-account.4.sample.pass.json
    │   ├── pre-account.4.with-null.pass.json
    │   ├── prio.4.reference.pass.json
    │   ├── prio.4.sample.pass.json
    │   ├── shield-icq-v1.4.error.pass.json
    │   ├── shield-icq-v1.4.progress.pass.json
    │   ├── sync.4.badcreationdate.pass.json
    │   ├── sync.4.badhistogramtypes.fail.json
    │   ├── sync.4.desktophistogram.fail.json
    │   ├── sync.4.desktophistogram.pass.json
    │   ├── sync.4.migration.pass.json
    │   ├── sync.4.minapplication.pass.json
    │   ├── sync.4.nested_devices.pass.json
    │   ├── sync.4.noapplication.fail.json
    │   ├── sync.4.nondesktophistogram.fail.json
    │   ├── sync.4.null_device_version.pass.json
    │   ├── sync.4.sample.pass.json
    │   ├── sync.5.sample.pass.json
    │   ├── testpilot.4.sample.pass.json
    │   ├── third-party-modules.4.minimal.pass.json
    │   ├── third-party-modules.4.moduleindex.fail.json
    │   ├── third-party-modules.4.sample.pass.json
    │   ├── third-party-modules.4.stackframe.fail.json
    │   ├── third-party-modules.4.trustflags.fail.json
    │   ├── third-party-modules.4.unknownmodule.pass.json
    │   ├── uninstall.4.sample.pass.json
    │   ├── untrusted-modules.4.minimal.pass.json
    │   ├── untrusted-modules.4.moduletrustflags.fail.json
    │   ├── untrusted-modules.4.sample.pass.json
    │   ├── untrusted-modules.4.stackframe.fail.json
    │   ├── untrusted-modules.4.unknownmodule.pass.json
    │   ├── update.4.ready.pass.json
    │   ├── update.4.success.pass.json
    │   ├── voice-feedback.4.normal.pass.json
    │   ├── voice.4.full.pass.json
    │   ├── voice.4.minimal.pass.json
    │   └── xfocsp-error-report.4.sample.pass.json
    └── webpagetest
        ├── webpagetest-run.1.median_only.pass.json
        ├── webpagetest-run.1.missing_firstview.fail.json
        ├── webpagetest-run.1.missing_metric_value.fail.json
        └── webpagetest-run.1.sample.pass.json

496 directories, 1057 files
