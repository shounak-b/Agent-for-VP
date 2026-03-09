# Step 8: Add Writing Instructions Under Each Headline

**Goal:** Provide context and guidance under each headline to direct the content writer on what should be discussed, explained, or highlighted in each section.

---

## Why This Matters

Writing instructions bridge the gap between the headline structure and the final content. They give writers clear direction on:
- What information to include under each heading
- How to frame the content (challenge/solution, explanation, technical details)
- What products, capabilities, or workflows to reference
- The depth and focus of each section

This ensures consistency, accuracy, and alignment with the Page Content Brief Guide.

---

## Prerequisites

Ensure you have:
- **Complete content brief with headline structure** (from Step 7)
- **Page Content Brief Guide** (from Step 1)
- **Primary and Secondary Keywords** (from Step 1)
- **Competitor headlines and insights** (from Step 6)
- **Existing page content** (from Step 5, if applicable)

---

## Instructions

### A. Read Saved Content Brief

Read the content brief file saved in Step 8:

**File path:**
```
./Briefs/<folder-name>/content-brief.md
```

Extract the headline structure from the HEADLINE STRUCTURE section.

---

### B. Generate Instructions for Each Headline

For each headline in the structure, write a single-paragraph instruction that explains what the content writer should cover in that section.

**Format requirements:**
- **Single paragraph** — No line breaks within the instruction (easy to copy/paste into Google Docs)
- **Target length** — 600-800 characters for H2 sections, can be shorter for H3s
- **Tone** — Technical, outcome-focused, references specific capabilities
- **Content** — What will be discussed, explained, demonstrated, or highlighted

---

### C. Apply Special Rules by Heading Type

#### **First H1 (Main headline):**
- **No instruction** — The H1 stands alone with no context beneath it
- Skip directly to the first H2

#### **First H2 only:**
- **Challenge → Solution format**
- First part: Introduce the challenge or problem that the target audience faces
- Second part: Present the solution or approach that addresses the challenge
- Frame from the audience's perspective
- Reference specific workflow stages or business outcomes

**Example pattern:**
```
[Problem statement describing challenges the audience faces]. [Solution statement explaining how integrated approaches/platforms/capabilities help address these challenges]. [Additional context on benefits or alignment with manufacturing goals].
```

#### **All other H2s:**
- Explain what the section will cover
- Reference specific products, platforms, or capabilities when relevant
- Describe technical aspects or workflow connections
- Connect to business outcomes or process goals
- May reference how the section relates to upstream/downstream operations

#### **All H3s:**
- Provide context for the subtopic
- Can be more specific than parent H2
- Reference technical details, specific products, or process parameters
- Explain how this subtopic relates to the broader section theme

---

### D. Use Reference Materials

**To ensure accuracy, reference:**

1. **Existing page content** (from Step 5, if available):
   - Review how topics were previously explained
   - Identify product mentions, technical terms, and workflow descriptions
   - Ensure important context isn't lost

2. **Competitor content insights** (from Step 6):
   - Note how competitors frame similar topics
   - Identify gaps or unique angles Visual Planning can emphasize

3. **Page Content Brief Guide** (from Step 1):
   - Align instructions with target audience needs
   - Reference specific products, services, or capabilities mentioned in the guide
   - Ensure instructions support the content goal

4. **Brand guidelines** (brand-guidelines.md):
   - Use outcome-driven language
   - Avoid prohibited terminology in instructions
   - Frame capabilities confidently without guarantees

---

### E. Format the Enhanced Content Brief

Create a new version of the content brief with instructions added under each headline.

**Structure:**

```markdown
# [Page Name from Step 1]

[Contact us link if applicable]

[Download link if applicable]

## [First H2 headline]

[Challenge → Solution instruction paragraph on single line]

## [Second H2 headline]

[Context instruction paragraph on single line]

### [H3 under Second H2]

[Context instruction paragraph on single line]

### [Another H3 under Second H2]

[Context instruction paragraph on single line]

## [Third H2 headline]

[Context instruction paragraph on single line]

[Continue with all sections...]

## Frequently asked questions

[Instructions for FAQ section approach]

### [FAQ question 1]

[Instruction for how to answer this FAQ]

### [FAQ question 2]

[Instruction for how to answer this FAQ]

[Continue for all FAQs...]

## Related pages

[List of relevant internal links from Step 4]
```

**Do NOT include:**
- Character count comments (those are added during actual writing)
- Placeholder text
- Meta information like word count targets or SEO notes

---

### F. Save the Enhanced Brief

Save the enhanced content brief with instructions as a new file:

**Filename:** `content-brief-with-instructions.md`
**Location:** Same folder as the original brief

**Full path:**
```
./Briefs/<folder-name>/content-brief-with-instructions.md
```

**Example:**
- Page Name: "CHO Cell Culture Media"
- Folder: `cho-cell-culture-media`
- Filename: `content-brief-with-instructions.md`
- Full path: `./Briefs/cho-cell-culture-media/content-brief-with-instructions.md`

---

## Output Format

After saving, display:

```
=== ENHANCED CONTENT BRIEF WITH INSTRUCTIONS CREATED ===

Folder: ./Briefs/<folder-name>/
File: content-brief-with-instructions.md
Full path: ./Briefs/<folder-name>/content-brief-with-instructions.md

Status: ✓ Successfully saved

Instructions added under:
- [X] H2 headlines (including challenge-solution for first H2)
- [X] H3 headlines
- [X] FAQ sections

---

The enhanced content brief is ready for the content writer.
```

---

## Quality Checks

Before saving, verify:

- [ ] First H1 has no instruction (stands alone)
- [ ] First H2 uses challenge → solution format
- [ ] All other H2s have context instructions
- [ ] All H3s have context instructions
- [ ] Each instruction is a single paragraph (no line breaks)
- [ ] Instructions are 600-800 characters for main sections
- [ ] Instructions reference specific products/capabilities where relevant
- [ ] Instructions align with Page Content Brief Guide
- [ ] Instructions incorporate insights from existing content (if available)
- [ ] Instructions follow brand guidelines tone
- [ ] Filename is `content-brief-with-instructions.md`
- [ ] File saved in correct folder

---

## Example Instruction Styles

### First H2 (Challenge → Solution):
```
Most teams outgrow their planning tools before they realize it — schedules split across spreadsheets, whiteboards, and email threads create gaps that lead to missed deadlines and resource conflicts. Visual Planning's configurable, visual-first scheduling platform helps operations and project teams replace disconnected tools with a single, collaborative system they can adapt to their workflow without programming. Moving to a centralized platform supports better visibility across teams, faster response to changes, and fewer errors caused by outdated or duplicate data.
```

### Regular H2 (Context):
```
Visual Planning's drag-and-drop scheduling interface is designed to give resource planners and operations managers a real-time view of who is working on what, when, and where. Users can configure views by role, project, department, or location — so each team member sees the information most relevant to their responsibilities. Smart assignment rules can filter resources by availability, skills, and location to help planners find the right person for the right task quickly. This section should explain how the scheduling interface works in practice and how it fits into a typical resource planning workflow.
```

### H3 (Specific Context):
```
Visual Planning's assignment rules allow planners to define criteria — such as skill set, certification, location, or shift availability — so the platform can surface eligible resources automatically. Rather than manually cross-referencing spreadsheets or calling team members to check availability, planners can filter and assign directly within the scheduling view. This subtopic should explain how rule-based assignment reduces manual effort, helps prevent double-booking, and supports more consistent scheduling decisions across teams.
```

---

## Error Handling

**Cannot read content brief from Step 8:**
- Verify the file path is correct
- Check that Step 8 completed successfully
- If file not found, cannot proceed with Step 9

**Insufficient context to write instructions:**
- Use the headline structure as-is
- Write general instructions based on headline topics
- Note limitations in output message

**File write fails:**
- Display error message
- Show the enhanced content so user can manually save

---

## Writing Tips

**For technical sections:**
- Reference specific products, platforms, or technologies
- Describe process parameters or technical considerations
- Explain how the section connects to broader workflows

**For business outcome sections:**
- Focus on efficiency, scalability, risk reduction, time to market
- Connect technical capabilities to business value
- Reference regulatory alignment or manufacturing requirements

**For application sections:**
- Describe what the section will demonstrate or explain
- Reference target workflows or use cases
- Connect to audience pain points or goals

**Maintain consistency:**
- Use similar phrasing patterns across related sections
- Keep technical depth consistent within heading levels
- Align with Visual Planning's messaging pillars where relevant (see brand-guidelines.md)

---

## Next Step

The enhanced content brief with writing instructions is now ready for handoff to the content writer for execution.
