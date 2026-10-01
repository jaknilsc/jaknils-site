# Jakob Nilsson website

A responsive static website for GitHub Pages. No build dependencies, tracking scripts or external fonts. Contact is through email and LinkedIn.

## Preview deployment

Publish `main` from the repository root in Settings → Pages. The preview is expected at https://jaknilsc.github.io/jaknils-site/.

The preview includes `noindex, nofollow` to discourage search indexing. This is not access control: the preview and repository are public.

## Before launch

- Review all copy and add a real portrait and approved examples of work if desired.
- Remove the robots noindex directive when ready for public search indexing.
- Add final canonical and social sharing metadata for the approved domain.
- Verify the domain in GitHub, then configure the custom domain in Pages before changing web DNS records.
- Preserve email-related MX and TXT records. Check HTTPS and both apex and www addresses after the switch.
- Keep a record of the previous web DNS configuration for rollback.

No custom domain or CNAME is configured for the preview. The current jaknils.com website is independent of this repository.