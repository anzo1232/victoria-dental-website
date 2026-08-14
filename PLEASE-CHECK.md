# Please check these before the site goes live

Everything on the new site is taken from the current victoriadentalpractice.net.
Nothing has been invented. But the old site contradicts itself in a few places,
and in each case I had to pick one version. These are the ones to confirm with
the practice.

---

## 1. Two different emergency fees

The old **Emergencies** page says an emergency visit for a new patient is
**£60.00**. The old **Treatments** page says an emergency appointment for a
patient not registered with the practice is **£65.00**.

**I used £65** on both pages, on the assumption the structured fee list is the
one that gets updated. If £60 is right, it appears twice: `emergencies.html`
and `treatments.html` (in the "Emergency appointments" group).

## 2. Two different treatment prices for the same work

The old Emergencies page and the old Treatments page disagree substantially:

| Treatment | Emergencies page | Treatments page |
|---|---|---|
| Fillings | from £75.00 | from £120.00 |
| Extractions | from £88.00 | from £125.00 |

**I used the Treatments page figures throughout** and removed the second set,
so the site now quotes one price per treatment. The emergency page lists only
the appointment fee and points at the main price list. Worth confirming the
emergency page figures are simply out of date rather than a genuinely lower
emergency rate.

The old emergency page also listed "Temporary filling from £37.00" and
"Prescription £34.00", which do not appear on the main fee list at all. I have
left both off — add them back to `treatments.html` if they are current.

## 3. The team page and the homepage name different people

The old **team page** lists three dentists: Sophie Allcock (GDC 82255),
Elizabeth Allcock (GDC 112754) and Irvina Ariaratnam (GDC 104617).

The old **homepage** text names Geoff Brooke-Jones as principal, Lynn as
practice manager, Vivien Geary as hygienist and Caroline as head nurse — none of
whom appear on the team page.

**I used the team page**, on the assumption the homepage text is older. The new
`team.html` has the three dentists with short bios I have drafted from their
listed qualifications, plus a general section about nurses, hygienist and
reception without naming anyone.

Two things to do here:

- Confirm the three dentists are current, and check the bios read accurately —
  they are my wording, not theirs, and should be edited freely
- Add the hygienist, nurses, manager and receptionists by name if the practice
  is happy to. Named faces are one of the strongest trust signals a dental
  website has, and it is a shame to lose the "thirty years at this practice"
  stories that were on the old homepage

## 4. How far is Fratton station?

The old homepage says Fratton is "just a 5 min walk away". The old contact page
says it is "a 15 minute walk away". **I have written "a short walk"** on both
pages rather than pick a number. Please replace with the real figure — it is a
useful detail for new patients.

## 5. Opening hours

The only hours published on the old site are **Monday to Friday, 8.30–5.00**, on
the contact page. Some third-party directories list Saturday and Sunday hours
for the practice, which I assume is wrong.

**I have shown Mon–Fri 8.30–5.00 and marked the weekend closed**, and the live
"open now / closed now" badge is built on those times. If you open on Saturdays,
or close for lunch, tell me and I will update all three places plus the
structured data Google reads.

## 6. Things the old site did not have, which I have added

These are new, and need a decision rather than a correction:

- **A privacy notice with actual content.** The old site linked to a privacy
  page; the new one contains a standard dental-practice notice covering what is
  held, why, how long, and patient rights. **It is a template and must be
  reviewed** against the practice's real retention schedule and ICO
  registration before publishing.
- **NHS 111 signposting** for out-of-hours emergencies on `emergencies.html`.
- **First-aid advice** for a knocked-out tooth, toothache and a lost crown.
  Clinically standard, but worth a dentist's eye over the wording.
- **A "second opinions" section**, drawn from the old homepage's mention that
  second opinions are welcome. I have said a consultation carries the standard
  new patient examination fee — confirm that is how you charge it.
- **The claim "over 50 years"** comes from the old homepage's "established over
  50 years ago". I have avoided naming a founding year anywhere.

## 7. Not carried over

- **The photo gallery.** The old site had a Gallery page of small practice
  photographs. The new site has no photography at all yet — see the
  photography note in the README. Send me the images and I will build a proper
  gallery in.
- **The CQC registration.** A CQC listing exists for the practice but was not on
  the old website. Adding your CQC provider ID and a link to your inspection
  report is a strong trust signal and takes one line.
- **Denplan branding.** The old site linked to Denplan. The new site describes
  Denplan and links to denplan.co.uk, but if the practice has an official
  Denplan member logo, it should go on `treatments.html`.
