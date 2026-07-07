# jj-jakub.github.io

Developer site for Android apps by Jakub Jasinski.

Hosts a single `app-ads.txt` (IAB Tech Lab spec) that authorizes AdMob to sell
ad inventory across **all** apps under the developer's AdMob account — one file
covers every app. Each app's Google Play "Website" field points at this domain.

- Live site: https://jj-jakub.github.io
- app-ads.txt: https://jj-jakub.github.io/app-ads.txt

## Adding another app

1. Add a card to `index.html`.
2. Point the new app's Play Console **Website** field at `https://jj-jakub.github.io`.
3. No change to `app-ads.txt` is needed unless the app uses a different AdMob
   publisher account (add its `google.com, pub-XXXX, DIRECT, ...` line) or a new
   mediation network (add the network's line).
