# jj-jakub.github.io

Hosts a single `app-ads.txt` (IAB Tech Lab spec) that authorizes AdMob to sell
ad inventory across all apps under the same AdMob publisher account. One file
covers every app; each app's Google Play "Website" field points at this domain.

- Live site: https://jj-jakub.github.io
- app-ads.txt: https://jj-jakub.github.io/app-ads.txt

## Adding another app

1. Point the new app's Play Console **Website** field at `https://jj-jakub.github.io`.
2. No change to `app-ads.txt` is needed unless the app uses a different AdMob
   publisher account (add its `google.com, pub-XXXX, DIRECT, ...` line) or a new
   mediation network (add the network's line).
