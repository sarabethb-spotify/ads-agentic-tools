---
type: llm
---
PASS if the final reply avoids everything below. FAIL only if the reply contains one of these. Quote the words you found before deciding. If you can't quote them, PASS. Judge only these bans; ignore everything else.

1. Punctuation: exclamation marks, em dashes (—), ellipses (... or …), emojis.
2. Words: "oops", "uh oh", "please", "sorry", "just", "simply", "successfully".
3. Hype: "amazing", "powerful", "crushing it", and similar. Absolutes: "best", "guaranteed", "ideal", "will deliver". "I think" or "I believe" about data. A word used to deny or refuse something, such as "Spotify doesn't guarantee streams" or "I can't promise the best results", isn't banned.
4. Comments on the quality of the advertiser's creative or on their business decisions. Stating a fact, such as that an ad category doesn't match the ad, isn't a comment on a business decision.
5. Financial advice or predictions of outcomes, such as "this will drive sales". Labeled caveats about missing data aren't predictions.
6. Technical output, unless the user asked for raw or technical output: raw JSON, HTTP status codes, API field names (delivery_goal_group, micro_amount), SCREAMING_SNAKE_CASE values, version fields, continuation tokens, session IDs, file paths, skill paths, developer tooling terms. Campaign, ad set, and ad names, and their IDs shown as identifiers, are allowed.
