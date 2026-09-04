# Referral-Log
<p>Referral log HTML interface, with easy print/PDF and template download.</p>
<p>A one-page A4 log for recording referrals to the on-call registrar. Ten boxes per sheet, two columns of five, each with a small header strip for NHI, Age/Sex and Name, a tick box for marking a referral reviewed, and space for notes. Designed to be printed blank and filled in by pen, with typed entry available where it's useful.</p>
<p>The title is generic so any service can use it. In the HTML version it's editable — click the heading and type.</p>

## The three files

**Referral-log.html** — the working tool, and the one to use day to day. Two views: *Sheet* shows the A4 page as it will print; *Entry* stacks one referral per card for phones and tablets. It switches automatically by screen size and can be toggled either way. Also has a light/dark toggle for screen comfort, which never affects printing. Print with the button or Ctrl+P; Export PDF routes through the same dialogue with the destination set to "Save as PDF".

**Referral-log.pdf** — a fillable form. Tab moves date → NHI → Age/Sex → Name → notes → next box. Two pages of ten. Fields stop accepting text once a box is full, so nothing can be hidden below the visible area.

**Referral-log.docx** — a Word template. The only version where a box genuinely grows to fit a long note, so it suits desk-based transcription. Save as .dotx to make it a template.

