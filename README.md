# cachet ($CACHET)

Single-file site: `index.html` (no build step). Deploy as-is on Vercel or GitHub Pages.

## Set your links
Open `index.html`, find the CONFIG line near the top of the script:

```js
var CONFIG={xUrl:'',xHandle:'',ca:'',buyUrl:''};
```

- `xUrl`: your X profile link
- `ca`: contract address (leave blank until launch; the page says "posted on X at launch")
- `buyUrl`: buy link once live

Empty links show a "soon" toast instead of breaking.

## Notes
- Coins, prices and creator earnings are labelled samples. The fee split (0.6%: 0.30% creator / 0.20% trader rebate / 0.10% platform) is labelled as planned.
- Footer states cachet is independent and not affiliated with pump.fun.
