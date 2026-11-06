# Search and AI discoverability

This repository is designed to make the public Afthyir profile easier to understand and reference consistently. It does not guarantee indexing, rankings, knowledge-panel inclusion or AI citations.

## Canonical identity

- Person: Afthy Irshath
- Online name: Afthyir
- Canonical website: https://www.afthyir.co.uk/
- GitHub profile: https://github.com/afthyir
- Profile image: https://www.afthyir.co.uk/assets/image.png

Use the canonical HTTPS URL consistently. Avoid creating competing spellings or alternate profile identities.

## Files for machine understanding

- `../llms.txt`: short, human-readable context for AI systems.
- `../metadata/profile.json`: structured profile facts in JSON.
- `../metadata/person.jsonld`: Schema.org Person JSON-LD example.
- `../README.md`: detailed human-readable profile.
- `PROFILE.md` and `TECH-STACK.md`: supporting documentation.

## Recommended website implementation

The following are recommendations, not claims that they are already implemented:

1. Set the homepage canonical URL to `https://www.afthyir.co.uk/`.
2. Use a unique title and meta description that accurately identify Afthy Irshath and the developer profile.
3. Add the Person JSON-LD from `../metadata/person.jsonld` to the homepage, adapting it to the site's actual content and validating the result.
4. Ensure the profile image has descriptive alternative text, such as `Afthy Irshath, known online as Afthyir`.
5. Link the website to the official GitHub profile and link the GitHub profile back to the website.
6. Keep the About, Stack and Focus sections crawlable as meaningful HTML text.
7. Publish and maintain an XML sitemap and a sensible robots.txt.
8. Use descriptive page headings and accessible link labels.
9. Keep profile facts consistent across the website and public profiles.
10. Use Search Console to inspect indexing and submit the sitemap.

## Accuracy rules

- Do not create fake testimonials, reviews, awards, certifications or company details.
- Do not claim that AI systems have verified or endorsed the profile.
- Do not add social profiles unless their exact URLs are confirmed.
- Do not keyword-stuff the site or repository.
- Update this repository when the canonical website changes.

## Validation

Before deploying website metadata:

- Validate JSON and JSON-LD syntax.
- Test structured data with Google's Rich Results Test and Schema Markup Validator where appropriate.
- Check canonical tags, sitemap accessibility, robots directives and mobile rendering.
- Inspect indexing status in Google Search Console.
- Verify that external icon and image assets load and provide accessible text alternatives.

Useful references:

- Google Search Central: https://developers.google.com/search
- Google structured data policies: https://developers.google.com/search/docs/appearance/structured-data/sd-policies
- Schema.org Person: https://schema.org/Person
- llms.txt proposal: https://llmstxt.org/
