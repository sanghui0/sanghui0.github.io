---
title: ShortsCook Privacy Policy
---

# ShortsCook — Privacy Policy

> Effective date: 2026-10-23 · [한국어](/shortscook/privacy)

Note: The parts about browsing popular recipes, ingredient auto-fill from cooking steps, and Meta install measurement apply from the app version that includes those features.

ShortsCook (the "App") takes your privacy seriously. This policy explains how information is handled.

## 1. Information We Collect

The App has no sign-up. It does not collect your name, email, phone number, location, or advertising identifier (IDFA). The information the App processes is as follows:

- **YouTube video links**: YouTube video links that you share or paste
- **Recipes and photos you save**: recipe content, and photos you take or pick from your photo library
- **App usage statistics**: usage records such as app launches, recipe import attempts, successes and failures, and opening saved recipes, plus an identifier for the App installation and basic device information such as device model and OS version
- **Public YouTube recipe view information**: public video IDs and view times used for browsing popular recipes. Recipe content and photos that individuals wrote or edited, and viewers' names or accounts, are not included in the public list.
- **Input for extracting recipes and ingredients**: recipe text from the clipboard that you choose to import, and the cooking steps used for ingredient extraction when you tap "Auto-fill ingredients"
- **Ad install measurement information**: install and app activation information from the Meta SDK, an anonymous identifier for the App installation, and app, device, and OS information. IP addresses and similar data may be processed during network communication. The App does not read the IDFA or request App Tracking Transparency (ATT) permission.

## 2. Purpose of Processing and Where Data Is Stored

- **YouTube video links** are sent to our own server (Cloudflare Workers) to extract recipes. The server uses the YouTube Data API to look up the video's public description and pinned comment, then sends that text to the OpenAI API to organize it into ingredients and cooking steps. To respond quickly when the same video is requested again, the server keeps **only the extraction result for each video** for a limited period. This result does not include any information about who made the request.
- **Recipes and photos you save** are, by default, **stored inside your device**. However, when you tap "Auto-fill ingredients", the cooking steps you wrote are sent through our server to the OpenAI API to extract ingredients and amounts. When you import recipe text from the clipboard, the text you selected is sent along the same path to be organized into a recipe. These personal inputs and photos are not posted to the public popular recipes.
- **Popular recipes** show only original recipes that the server extracted from public YouTube descriptions and comments. Recent view information for public video IDs is used to sort the public list, and the remaining slots are filled from the existing public extraction cache. Personally edited recipes and recipes you wrote yourself are not shared. The existing public video information cache is kept for up to 30 days, and recent-view records are kept only for the limited period needed to operate the feature.
- **The clipboard** is checked only for whether text exists on the home screen; its contents are read only when you choose to import. When the system asks for paste permission, you decide whether to allow it. The content read is used only for the recipe import and extraction you selected.
- **The camera and photo library** are used only when you add a photo to a recipe, and only the photos you choose are stored on your device.
- **App usage statistics** are collected through Firebase Analytics by Google LLC to improve the App. They are not combined with information that identifies you, and they are not used for advertising or tracking. For details, see [Google's Privacy Policy](https://policies.google.com/privacy).
- **Meta install measurement** is used to measure results from ads to app installs and launches. IDFA collection, automatic purchase events, and codeless tracking are not used. For details, see [Meta's Privacy Policy](https://www.facebook.com/privacy/policy/).

## 3. Processors and Third-Party Provision

The App does not sell your information. To provide the service, we use the services of the following companies.

| Company | Processing |
|---|---|
| Cloudflare, Inc. | Operating the recipe extraction server |
| Google LLC (YouTube Data API) | Looking up a video's public description and pinned comment |
| OpenAI, L.L.C. | Organizing descriptions, comments, and recipe text you import; extracting ingredients from the cooking steps you wrote |
| Google LLC (Firebase Analytics) | App usage statistics |
| Meta Platforms | Measuring ad install and app activation results |

## 4. Your Rights

- You can edit or delete saved recipes in the App at any time.
- Deleting the App also deletes the recipes and photos stored on your device.
- You can turn off camera and photo access at any time in iPhone Settings > ShortsCook.

## 5. Children's Information

The App is not directed at children under 14 and does not knowingly collect their personal information.

## 6. Changes to This Policy

This policy may be updated to reflect changes in law, policy, or the service. Any changes will be announced on this page.

## 7. Contact

For questions about how personal information is handled, please contact:

- Email: tkdhi0107@gmail.com
