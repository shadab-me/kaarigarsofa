# Image prompts and where they go

Rule: AI images are fine for the fabric picture only. Never put an AI image in "Sofas we fixed this month". That section must hold real photos of your own jobs.

## 1. Fabric change picture (AI is OK)
Save as `img/fabric-change.webp`, 1600x1200, under 150 KB.
Prompt:
> Photorealistic photo, bright Indian apartment living room in Noida, a 3-seater sofa freshly reupholstered in textured warm grey chenille fabric with tidy piping, firm plump cushions, a fabric swatch book open on the floor beside it, natural window light, shallow depth of field, calm clean look, no people, no text, no logo, 4:3.

In `site/index.html`, in the `window.SITE` block set:
```
fabricImage: "img/fabric-change.webp",
fabricImageAlt: "Sofa reupholstered in grey chenille fabric",
```
It replaces the drawn before/after under "Keep the frame".

## 2. Real work photos (shoot with a phone, no AI)
Take 4 to 8 jobs: before, after, and the karigar at work (with the customer's OK). Landscape 4:3, window light, under 120 KB each as webp.
Save as `img/work/<job>-<sector>.webp`, then add to `photos`:
```
photos: [ { src: "img/work/recliner-sec137.webp", caption: "Recliner footrest fixed, Sector 137" } ]
```
The "Sofas we fixed this month" section appears by itself.

## 3. Social share picture
Replace `img/og.png` (1200x630) with a real after photo plus the logo.

## 4. Google Ads
Use the same real photos as image assets in the campaign. Fabric swatch close-ups work well too.
