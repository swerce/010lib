# 010lib

This is a lightweight CSS utility library designed to provide a set of convenient classes for common styling tasks, making it easy to create clean and responsive designs.

## Features

- Typography: Easily apply consistent typography styles.
- Colors: Access a variety of predefined text and background colors.
- Spacing: Apply margin and padding with predefined spacing classes.
- Flexbox: Create flexible and responsive layouts with flexbox classes.
- Grid: Utilize grid-based layouts with customizable column options.
- Shadows: Apply box shadows for depth and emphasis.
- Hover Effects: Add hover effects to enhance user interaction.
- Borders: Quickly add borders with customizable styles.
- Transitions: Apply smooth transitions to elements.
- Responsive Design: Use responsive classes to adapt to different screen sizes.

## How to Use

1. Include the CSS file in your project:

```html
<link rel="stylesheet" href="path/to/your/css/utility-library.css">
```
Aspect Ratio

    .aspect-ratio-16x9
    .aspect-ratio-4x3
    .aspect-ratio-1x1
    .aspect-ratio-3x2
    .aspect-ratio-8x5
    .aspect-ratio-2x1
    .aspect-ratio-9x16
    .aspect-ratio-3x4
    .aspect-ratio-5x8

Container

    .container
    .container-sm
    .container-md
    .container-lg
    .container-xl
    .container-fluid

Columns

    .col-{1 to 12}

Break After

    .ba-avoid
    .ba-auto
    .ba-left
    .ba-right

Break Before

    .bb-avoid
    .bb-auto
    .bb-left
    .bb-right

Break Inside

    .bi-avoid
    .bi-auto
    .bi-avoid-page

Box Decoration Break

    .bdb-slice
    .bdb-clone
    .bdb-initial
    .bdb-unset

Box Sizing

    .bs-border-box
    .bs-content-box
    .bs-initial
    .bs-unset

Display

    .d-block
    .d-inline
    .d-flex
    .d-inline-flex
    .d-none
    .d-list-item

Floats

    .fl
    .fl-right
    .fl-none

Clear

    .cl
    .cl-left
    .cl-right
    .cl-none

Isolation

    .isolate
    .isolate-auto

Object Fit

    .of-contain
    .of-cover
    .of-fill
    .of-none
    .of-scale-down

Object Position

    .op-center
    .op-top
    .op-right
    .op-bottom
    .op-left

Overflow

    .overflow-visible
    .overflow-hidden
    .overflow-scroll
    .overflow-auto

Overscroll Behavior

    .os-auto
    .os-contain
    .os-none

Position

    .position-static
    .position-relative
    .position-absolute
    .position-fixed
    .position-sticky

Top / Right / Bottom / Left

    .trbl-0
    .trbl-auto
    .trbl-right-0
    .trbl-right-auto
    .trbl-bottom-0
    .trbl-bottom-auto
    .trbl-left-0
    .trbl-left-auto

Visibility

    .v-visible
    .v-hidden
    .v-collapse

Z-Index

    .z-1
    .z-2
    .z-3
    .z-4
    .z-5

Word Break

    .wb-normal
    .wb-break-all
    .wb-keep-all
    .wb-break-word

Word Wrap

    .ww-normal
    .ww-break-word
    .ww-initial
    .ww-unset

White Space

    .ws-normal
    .ws-nowrap
    .ws-pre
    .ws-pre-line
    .ws-pre-wrap

Hover

    .hover-hover

Active

    .active-active

Focus

    .focus-focus

Visited

    .visited-visited

Disabled

    .disabled-disabled
    :disabled

Placeholder

    .placeholder-placeholder

Not Placeholder

    .not-placeholder-not-placeholder

Read Only

    .read-only-read-only

Read Write

    .read-write-read-write

Valid

    .valid-valid

Invalid

    .invalid-invalid

Required

    .required-required

Optional

    .optional-optional

Checked

    .checked-checked

Not Checked

    .not-checked-not-checked

Default

    .default-default

Indeterminate

    .indeterminate-indeterminate

Placeholder Shown

    .placeholder-shown-placeholder-shown

Target

    .target-target

Empty

    .empty-empty

First Child

    .first-child-first-child

Last Child

    .last-child-last-child

Only Child

    .only-child-only-child

First Of Type

    .first-of-type-first-of-type

Last Of Type

    .last-of-type-last-of-type

Only Of Type

    .only-of-type-only-of-type

Empty (Last Child)

    .empty-last-child-empty-last-child

Enabled

    .enabled-enabled

Disabled (Form Control)

    .disabled-form-control-disabled-form-control

Active (Form Control)

    .active-form-control-active-form-control

Checked (Form Control)

    .checked-form-control-checked-form-control

Focus (Form Control)

    .focus-form-control-focus-form-control

Valid (Form Control)

    .valid-form-control-valid-form-control

Invalid (Form Control)

    .invalid-form-control-invalid-form-control

Required (Form Control)

    .required-form-control-required-form-control

Optional (Form Control)

    .optional-form-control-optional-form-control

Selected

    .selected-selected

Checked (Toggle)

    .checked-toggle-checked-toggle

Small

    .small-small

Big

    .big-big

Active (Toggle)

    .active-toggle-active-toggle

Selected (Toggle)

    .selected-toggle-selected-toggle

Text Align

    .text-align-left
    .text-align-center
    .text-align-right
    .text-align-justify

Text Decoration

    .text-decoration-none
    .text-decoration-underline
    .text-decoration-overline
    .text-decoration-line-through

Text Transform

    .text-transform-uppercase
    .text-transform-lowercase
    .text-transform-capitalize
    .text-transform-none

Font Style

    .font-italic
    .font-normal
    .font-oblique

Font Weight

    .font-weight-bold
    .font-weight-bolder
    .font-weight-normal
    .font-weight-lighter

Font Size

    .font-size-1
    .font-size-2
    .font-size-3
    .font-size-4
    .font-size-5
    .font-size-6
    .font-size-7

Line Height

    .line-height-1
    .line-height-2
    .line-height-3
    .line-height-4
    .line-height-5
    .line-height-6

Letter Spacing

    .letter-spacing-1
    .letter-spacing-2
    .letter-spacing-3

Float (Responsive)

    .sm-fl-left
    .sm-fl-right
    .sm-fl-none

Clear (Responsive)

    .sm-cl-left
    .sm-cl-right
    .sm-cl-none

Display (Responsive)

    .sm-d-block
    .sm-d-inline
    .sm-d-flex
    .sm-d-inline-flex
    .sm-d-none

Visibility (Responsive)

    .sm-v-visible
    .sm-v-hidden

Z-Index (Responsive)

    .sm-z-1
    .sm-z-2
    .sm-z-3
    .sm-z-4
    .sm-z-5

Text Align (Responsive)

    .sm-text-align-left
    .sm-text-align-center
    .sm-text-align-right
    .sm-text-align-justify

Font Weight (Responsive)

    .sm-font-weight-bold
    .sm-font-weight-bolder
    .sm-font-weight-normal
    .sm-font-weight-lighter

Font Size (Responsive)

    .sm-font-size-1
    .sm-font-size-2
    .sm-font-size-3
    .sm-font-size-4
    .sm-font-size-5
    .sm-font-size-6
    .sm-font-size-7

Line Height (Responsive)

    .sm-line-height-1
    .sm-line-height-2
    .sm-line-height-3
    .sm-line-height-4
    .sm-line-height-5
    .sm-line-height-6

Letter Spacing (Responsive)

    .sm-letter-spacing-1
    .sm-letter-spacing-2
    .sm-letter-spacing-3

Background Color

    .bg-{color}
    .bg-transparent

Border Color

    .border-{color}
    .border-transparent

Text Color

    .text-{color}
    .text-transparent

Hover (Background Color)

    .hover-bg-{color}

Hover (Border Color)

    .hover-border-{color}

Hover (Text Color)

    .hover-text-{color}

Active (Background Color)

    .active-bg-{color}

Active (Border Color)

    .active-border-{color}

Active (Text Color)

    .active-text-{color}

Focus (Background Color)

    .focus-bg-{color}

Focus (Border Color)

    .focus-border-{color}

Focus (Text Color)

    .focus-text-{color}

Placeholder (Color)

    .placeholder-{color}

Read Only (Color)

    .read-only-{color}

Read Write (Color)

    .read-write-{color}

Valid (Color)

    .valid-{color}

Invalid (Color)

    .invalid-{color}

Required (Color)

    .required-{color}

Optional (Color)

    .optional-{color}

Checked (Color)

    .checked-{color}

Not Checked (Color)

    .not-checked-{color}

Default (Color)

    .default-{color}

Indeterminate (Color)

    .indeterminate-{color}

Placeholder Shown (Color)

    .placeholder-shown-{color}

Target (Color)

    .target-{color}

Empty (Color)

    .empty-{color}

First Child (Color)

    .first-child-{color}

Last Child (Color)

    .last-child-{color}

Only Child (Color)

    .only-child-{color}

First Of Type (Color)

    .first-of-type-{color}

Last Of Type (Color)

    .last-of-type-{color}

Only Of Type (Color)

    .only-of-type-{color}

Empty (Last Child) (Color)

    .empty-last-child-{color}

Enabled (Color)

    .enabled-{color}

Disabled (Form Control) (Color)

    .disabled-form-control-{color}

Active (Form Control) (Color)

    .active-form-control-{color}

Checked (Form Control) (Color)

    .checked-form-control-{color}

Focus (Form Control) (Color)

    .focus-form-control-{color}

Valid (Form Control) (Color)

    .valid-form-control-{color}

Invalid (Form Control) (Color)

    .invalid-form-control-{color}

Required (Form Control) (Color)

    .required-form-control-{color}

Optional (Form Control) (Color)

    .optional-form-control-{color}

Selected (Color)

    .selected-{color}

Checked (Toggle) (Color)

    .checked-toggle-{color}

Active (Toggle) (Color)

    .active-toggle-{color}

Selected (Toggle) (Color)

    .selected-toggle-{color}

Text Align (Color)

    .text-align-{color}

Text Decoration (Color)

    .text-decoration-{color}

Text Transform (Color)

    .text-transform-{color}

Font Style (Color)

    .font-style-{color}

Font Weight (Color)

    .font-weight-{color}

Font Size





create a css utility librery write code with short class names not same class names like tailwind css firstley add these options to it :
