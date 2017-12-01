# System76 Style & Human Interface Guidelines

The Style & Human Interface Guidelines (SHIG) are designed to help our
developers and designers maintain a consistent and pleasant experience for end
users across our web and desktop products.


## Dialogs & Actions

When presenting a dialog or action, include Primary and Secondary text as well
as Actions.


### Primary Text

Basic information and a suggestion.


### Secondary Text

Further details, including any non-obvious consequences of actions.


### Actions

Aligned right-to-left at the bottom of the UI. Affirmative/suggested action,
cancel (if applicable), and any secondary actions.


## Common Terms to Use & Avoid

### Products

If you are unable to know the explicit type, use the generic term
"product" when referring to a customer's product. Avoid semi-generic terms like
"computer". If you can determine whether it's a laptop, desktop, accessory,
etc., use that more specific term. If you know the specific product, use its
product name when it makes sense.


### Payment Methods

Use the term "payment methods", not "transaction methods", "payment cards", or
anything else when being generic. If you know the type of a specific payment
method in context (i.e. a card or financing), feel free to be more specific.
However, avoid "credit card" or "debit card", since we can't distinguish between
the two; instead, just say, "card".


## Measurements & Units

Use a space between numbers and text units, eg. `72 TB` and `4.0 GHz` instead of
`72TB` and `4.0GHz`. For feet and inches, use the prime (&prime;, `&prime;`) and
double-prime (&Prime;, `&Prime;`) entities. For pounds and kilograms, always
abbreviate, but do not use a period after the abbreviation, eg. use `2.5 lbs`,
not `2.5 lbs.`.


### Display & Camera Resolutions

When describing resolutions, always use a times symbol (&times;, `&times;`)
between the pixel width and height with no spaces, eg. "3200&times;1800".
Default to using the actual resolution (1920×1080, 3200×1800, 3840×2160, etc.)
and not more ambiguous terms.

To describe a high-density pixel-doubled screen, always use the term "HiDPI";
the fact that they are HiDPI is what matters, not the exact physical resolution.
Relegate exact pixel resolutions to tech specs or supplementary text.

When a shorthand for the resolution exists, use it when space is limited, but
**only** when it exactly matches what is in the table below. **Never** use it as
a replacement for the actual resolution in tech specs, as customers are looking
for the specific pixel resolutions there.

Resolution | Shorthand
---------- | ---------
1280×720   | 720p
1920×1080  | 1080p
2560×1440  | 1440p
3840×2160  | 4K
5120×2880  | 5K


### Money & Prices

Use whole dollar amounts for customer-facing pricing and copy. Only use cents
once taxes and/or shipping get involved (where we can't round them to the
dollar).


## Third-Party Brand Names

NVIDIA should always be written as `NVIDIA` in both component names and general
copy. Intel should include the registered symbol (&reg;, `&reg;`) i.e.
"Intel&reg;" in tech specs and catalog product option descriptions, but **not**
in component names or general copy.

---

The System76 HIG is heavily influenced by [elementary](https://elementary.io).
For anything not covered in this document, refer to the [elementary
HIG](https://elementary.io/docs/human-interface-guidelines).
