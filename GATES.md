# GATES — property snapshot sheet (documents module, client app)

Leaf: rebuild #dkPropSheet as 1:1 port of the office-app client-snapshot bottom sheet,
with documents-module content (envelopes → own docs + own signing order).
OWNS: radius-client-app.html, scraps/client-inner-live.html, backup/radius-client-app.backup.html

G1  Chevron on a property row (Documents → By property) opens the snapshot sheet.
    CHECK: manual — click .dk-prow, #dkPropSheet gets .on
G2  Sheet chrome = office metrics: .sheet-grab, .sheet-head (44px property tile, .sh-name 700/17,
    .sh-sub role+status pstat pills, 32px .sheet-x), radius 22px, max-height 93%.
G3  .sh-ins Mel insight card: 30px bulb tile, .ins-h with <em> primary highlight, .ins-d. No action links.
G4  .sh-tabs segmented (28px pills in muted track): In progress · Completed · Activity;
    selected tab = white + shadow-xs; red .sh-dot on In progress when action is on the client.
G5  Every envelope is one card that owns: mail tile, title, status rds-badge, meta,
    its own signing-order dot row, its own document rows, its own action row.
    No document is listed flat at sheet level.
G6  Per-document action is explicit: Sign / View / Upload chip per row.
G7  Envelope states all present for 12 Oak: (a) needs your signature, (b) you signed → waiting on others,
    (c) completed by all. 220 Pine: agent-requested upload, no envelope.
G8  Completed tab: completed envelope + completed document rows. Activity tab: day-grouped
    feed cards with the envelope chip on each event.
G9  Exactly one sticky CTA (.sheet-cta button, 46px indigo pill) = Open property.
G10 Bundle round-trips: radius-client-app.html template re-parses, no console errors.

ABANDON: none
