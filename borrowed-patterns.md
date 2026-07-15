# Borrowed patterns: Captain Key Largo

Reference builds read IN FULL before building: Big Truck A/C Shop (C:\Users\accc0\Downloads\Agency\Clients\BigTruck\index.html, 739 lines) and JOTL (C:\Users\accc0\Downloads\JOTL\index.html, 2620 lines).

## 1. Statement grid (BigTruck lines 149-158, 368-379)
`.statement-grid` two-column headline + body pattern. Used for the "Don't rent a boat" section (CKL lines ~330-345). Re-skinned: Barlow Condensed uppercase headline with coral em, sand background instead of bone.

## 2. Alternating photo/text band architecture (BigTruck lines 160-183, 381-413)
The `.band` grid with photo order-swapping became the Dawn-to-Dark rail bands, extended with a third sticky "time" column that BigTruck does not have (CKL `.dayband`, lines ~200-250 CSS). Re-skinned: white background, coral time-clock labels, square icon frames.

## 3. Owner timeline (BigTruck lines 205-212, 436-441)
`.timeline` year/description rows became `.cap-marks` in the captain section. Re-skinned: light background, coral year numerals in Barlow Condensed, non-year marks ("40+", "100T").

## 4. Accordion + drawer + anchor/hash JS (BigTruck lines 235-243, 654-716)
Single-open max-height accordion, body-scroll-lock drawer, hash-stripping smooth scroll, and resize re-measure copied nearly verbatim (proven mobile-safe engineering). Drawer re-skinned to navy with numbered condensed links and white phone pill (pill pattern from JOTL drawer-footer, lines 307-321).

## 5. Mailto form with JS validation (JOTL lines 2593-2615 + BigTruck lines 718-736 merged)
BigTruck's branded field-level validation combined with JOTL's mailto submission so inquiries actually reach the owner on a static host. Re-skinned error copy to the captain's voice.

Not borrowed: colors, headline copy, hero concept, signature element, fonts.
