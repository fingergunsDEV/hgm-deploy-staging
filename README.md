# hgm-deploy-staging

Index of Holistic Growth Marketing site deploy ZIPs.

**The ZIPs themselves live in Google Drive: [HGM deploy staging](https://drive.google.com/drive/folders/1GC1hpQ_nJbnKMVjtGycCN0iYZz4mYfc_)**
— every finished package lands there automatically, so it can be downloaded anytime.
This repo tracks what's what.

## Packages

| File | Date | Contents |
|------|------|----------|
| hgm-deploy-fullwidth-2026-10-03.zip | 2026-10-03 | Full site (191 files): full-width homepage, fluid gutters, full-bleed footer (content unchanged), neumorphic Light/Dark/Agentic theme controls + matching a11y controls, theme.js homepage fix, real newsletter submission, 241 Facebook-link corrections to facebook.com/holisticgrowthmarketingllc |

## Deploying a package

1. Download the ZIP from the Drive folder.
2. Upload it via Bluehost File Manager and extract into public_html.
3. Fix permissions after extract: File Manager > public_html > Select All > Change Permissions > 755 recursive
   (a cron job running fix-perms.php normalizes them back to 644/755 within minutes).
