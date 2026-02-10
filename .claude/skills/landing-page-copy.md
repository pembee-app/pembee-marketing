# Landing Page Copy Generator

Create conversion-focused landing page copy for Pembee.

## Instructions

1. Read `context/CLAUDE.md` for brand voice, pricing, and business context.
2. Ask the user for:
   - **Page type** (vertical-specific, feature-focused, comparison, campaign)
   - **Target vertical** if applicable
   - **Target audience segment**
   - **Primary conversion goal** (free trial signup, demo request, etc.)
3. Generate landing page copy following this structure:

### Page Structure

#### Hero Section
- **Headline:** Benefit-led, speaks to the target audience's #1 pain point (under 10 words)
- **Subheadline:** Expands on the headline, introduces Pembee as the solution (under 25 words)
- **CTA button text:** Action-oriented (e.g., "Start your free trial")
- **Supporting text:** "30-day free trial. No credit card required."

#### Problem Section
- 3 pain points the target audience faces
- Written from their perspective ("Sound familiar?")

#### Solution Section
- How Pembee solves each pain point
- Feature highlights with benefit-focused descriptions
- Use concrete outcomes, not abstract promises

#### Social Proof
- Suggest placement for testimonials, logos, or stats
- Write placeholder testimonial copy if needed

#### Feature Breakdown
- 3-4 key features with short descriptions
- Each tied to a tangible benefit

#### Pricing Preview
- Brief pricing mention with link to full pricing page
- Lead with "From $45/month" and the free trial

#### Final CTA
- Repeat the primary CTA
- Add urgency or reassurance ("Join hundreds of activity providers" / "Set up in minutes")

4. Save to `output/landing-page/{YYYY-MM-DD}-{slug}.md`

## Vertical-Specific Guidelines

When writing for a specific vertical, use language and examples specific to that vertical. Reference the vertical landing pages listed in the business context.
