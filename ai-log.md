# AI Assistance Log

## Purpose

Record AI assistance used for the SWE 325/525 Career-Fair Resume
Website assignment.

I remain responsible for checking resume facts, reviewing changes,
testing the website, and following the assignment's AI-use rules.

## Interaction 1 — Assignment planning and Git workflow

- Date range:
  October 16–18, 2026.

- Tool:
  Perplexity.

### Purpose

Understand the assignment and organize a no-terminal workflow using
GitHub Desktop, Replit, GitHub Issues, pull requests, and GitHub Pages.

### Prompt summary

I asked for help interpreting the assignment, connecting Replit with
GitHub, preserving the instructor template, and incorporating content
from an earlier Weebly website.

### What I accepted

- Use my fork of the instructor's repository as the project base.
- Use GitHub Desktop for the required local clone.
- Use Replit as the editing workspace.
- Publish the final website using GitHub Pages.
- Create the six required GitHub issues.
- Use feature branches and pull requests for changes.

### What changed during the interaction

The initial guidance assumed the repository would use main.
Inspection showed that the imported repository used master.
The workflow was adjusted, and the GitHub default branch was renamed
to main.

An earlier plan treated the Replit configuration commit as unpushed.
A later GitHub check showed it was already on the remote repository.
The plan was corrected to avoid a redundant recovery pull request.

### What I rejected or deferred

I requested only the necessary issues and did not proceed with an
additional setup issue or Project board.

### Verification and limitations

GitHub Desktop screenshots later showed main selected and no
uncommitted changes. These screenshots alone do not prove that the
remote URL, initial website behavior, or deployed site was checked.

## Interaction 2 — GitHub issue wording

- Date:
  October 17, 2026.

- Tool:
  Perplexity.

### Purpose

Prepare clear task descriptions for the six required work categories.

### Prompt summary

I requested copy-and-paste issue titles, checklists, acceptance criteria,
and creation instructions without additional project-management work.

### What I accepted

I created these issues in JoMEngAI/websitetemplate:

1. Replace template identity and introduction content.
2. Add education, skills, experience, and project information.
3. Update images, links, and resume PDF.
4. Improve visual consistency and responsive layout.
5. Test links, navigation, accessibility, and mobile layout.
6. Deploy and verify the GitHub Pages website.

### What I changed

No additional wording changes are documented in this log.
If I revise the issue descriptions, I will record significant changes.

### What I rejected or deferred

Additional issues, labels, milestones, and a Project board were not
needed for this stage.

### Verification

Perplexity checked GitHub and confirmed that all six issues existed
and were open. Their existence does not mean their tasks are complete.

## Interaction 3 — Content plan and initial AI log

- Date:
  October 18, 2026.

- Tool:
  Perplexity.

### Purpose

Draft content-plan.md and ai-log.md using my resume, the assignment,
and the actual project history.

### Prompt summary

I requested copy-and-paste file contents and instructions for where
to save the files.

### Assistance provided

- Suggested a concise professional summary.
- Organized education, experience, and six core skill groups.
- Proposed two professional case studies grounded in my resume.
- Marked missing information rather than inventing it.
- Prepared this initial AI-use record.

### Acceptance status

Draft received. Final acceptance and factual review are pending.

### What I changed

To be completed after I review and edit the drafts.
Do not interpret this field as confirmation that no changes are needed.

### What I rejected

No specific draft content has been rejected at the time of this entry.
Record any rejected suggestions and reasons after review.

### Items requiring my confirmation

- Expected MS graduation date.
- Final education and concentration wording.
- Public contact method.
- Public-safe resume PDF and location.
- Approval of employer information and any published metrics.
- Accuracy and appropriateness of the proposed project descriptions.

## Replit assistance observed so far

The imported-project Agent inspected the project and described it as
a static HTML/CSS/JavaScript portfolio.

A commit named "Add Replit configuration file" was created.
Perplexity inspected its GitHub diff and reported that it added the
.replit configuration file.

I selected "Leave it as imported for now."
This log does not claim that website customization, deployment,
accessibility testing, or link testing has been completed.

## Ongoing responsibilities

- Review every proposed file change.
- Do not invent experience, dates, technologies, links, or results.
- Do not provide credentials or confidential employer information.
- Keep original private documents and export archives out of Git.
- Record actual testing separately from code inspection.
- Update this log as further AI assistance is used.
## Interaction 4 — Replit Agent website implementation

- Date:
  October 18, 2026.

- Tool:
  Replit Agent.

### Purpose

Turn the instructor template into my resume website using my resume
(Mendoza-Joseph_CV2026.pdf), the assignment PDF, my two planning briefs,
and my exported Weebly theme.

### Prompt summary

I told the Agent that the Weebly site archive was not available and asked
it to build the site now from the materials I had supplied.

### What the Agent did (not yet reviewed by me)

- Replaced the template author's identity, text, links, metadata, photo,
  resume PDF, and project/skill images with my content.
- Removed the old Google Tag Manager, Google Analytics, and Google
  site-verification tags.
- Removed the typing animation and the click-to-reveal project cards.
- Changed asset paths from absolute (/assets/...) to relative
  (assets/...) so they work under a GitHub Pages repository subpath.
- Restyled the site with a navy/teal palette. The Weebly "Oasis" theme
  export's blue preset (#185a9d / #43CEA2) was used as color inspiration
  only; no Weebly files were copied.
- Added an accessible mobile menu, skip link, and visible keyboard focus.
- Used three resume-based case studies (Perplexity research shared space,
  Oracle ERP vendor data cleansing, Medline SQL reporting automation).
- Did not publish my phone number, email, or location, and did not
  upload a resume PDF.

### Fact differences the Agent resolved in favor of my resume

- Savings pipeline: brief said $10M+; resume says $12M+. Site uses $12M+.
- Research time saved: brief said 100+ hours; resume says 150+ hours.
  Site uses 150+ hours.
- 24K Chef LLC was listed in my brief but is not in my resume, so it was
  left off the site.

### Acceptance status

On October 18, 2026 I approved these choices: LinkedIn and GitHub as the
only public contact methods, "request on LinkedIn" instead of a public
resume PDF, "2025 – Present (in progress)" for my MS, and public display
of the resume metrics. My review of the rest of the site content is still
pending. Nothing has been committed by me, pushed, or merged yet.

### Instructor clarification needed

The assignment allows AI for brainstorming, explanations, accessibility
suggestions, and review. This interaction went further: the Agent wrote
the site code and content. I should disclose this and confirm with the
instructor that it is acceptable.

### What I still need to verify personally

- Every resume statement and metric shown on the site.
- LinkedIn and GitHub links open the correct profiles.
- Desktop and mobile layout in my own browser.
