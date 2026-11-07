# Optional: replacing the illustrated banner with a real portfolio screenshot

The bundled illustrations are original artwork, **not screenshots**. This environment could not reach the live website through a headless browser.

On your own computer, after installing Playwright (`npm i -D playwright` and `npx playwright install chromium`), run:

```bash
npx playwright screenshot --browser chromium --viewport-size "1440,900" --wait-for-timeout 2500 https://www.kasomaibrahim.dev/ assets/portfolio-desktop.png
npx playwright screenshot --browser chromium --viewport-size "390,844" --wait-for-timeout 2500 https://www.kasomaibrahim.dev/ assets/portfolio-mobile.png
```

Then change the first README image from `./assets/profile-banner.png` to `./assets/portfolio-desktop.png`. Check the output manually for fonts, animation and any overlay.
