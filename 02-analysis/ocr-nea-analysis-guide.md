# OCR A Level Computer Science NEA: Step-by-Step Guide to Writing the Analysis

Here’s a practical step-by-step guide students can use for writing the **Analysis** section of the **OCR A Level Computer Science NEA**.

OCR’s programming project awards **10 marks** for the Analysis and expects students to cover four strands: **problem identification, stakeholders, research, and specifying the proposed solution**. ([ocr.org.uk](https://www.ocr.org.uk/Images/257212-crossover-reference-guide.pdf?utm_source=chatgpt.com)) The attached guide says this section should research the problem thoroughly, use methods such as product research, meetings and surveys, describe the essential features and limitations of the solution, develop requirements, and produce **measurable** success criteria. fileciteturn1file2L1-L10

## Step 1: Start with a clear problem statement

Open the Analysis with a short section explaining:

- what the real problem is
- who currently has the problem
- why it matters
- where the boundaries of your project are

The attached guide stresses that the problem must be clearly defined, including where the problem ends, because weak problem definition causes issues later with success criteria, design and testing. fileciteturn0file0L29-L29 fileciteturn1file4L1-L5

A good structure is:

**Problem:**  
“The current system for booking practice rooms at the school is paper-based and often results in double-bookings, missing records and wasted staff time.”

**Project boundary:**  
“This project will create a desktop booking system for staff and students in one department only. It will not include whole-school timetable integration.”

Write this in plain English, not marketing language.

## Step 2: Explain why the problem is suitable for a computational solution

OCR expects students to **describe and justify the features that make the problem solvable by computational methods** and explain why it is suited to a computational approach. ([ocr.org.uk](https://www.ocr.org.uk/Images/257212-crossover-reference-guide.pdf?utm_source=chatgpt.com)) The attached guide warns against generic comments and says students should explain the specific computational advantages for *this* problem. fileciteturn0file0L30-L30

So do not write:

“Computers are faster and more accurate.”

Write something like:

“This problem is suitable for a computational solution because the system must store large numbers of bookings, validate dates and times automatically, search existing records quickly, and prevent clashes in real time. These are repetitive rule-based tasks that a computer can perform consistently.”

This section should usually mention things like:

- storage and retrieval of data
- validation
- searching/sorting/filtering
- automation of repetitive decisions
- speed/accuracy/consistency
- real-time feedback
- reporting or visualisation where relevant

## Step 3: Identify the stakeholders properly

OCR expects students to identify and describe stakeholders and explain how the solution is appropriate to their needs. ([ocr.org.uk](https://www.ocr.org.uk/Images/257212-crossover-reference-guide.pdf?utm_source=chatgpt.com)) The attached guide says students should name stakeholders, describe their roles and interactions, and think carefully about whether they are suitable, available and knowledgeable enough to support the project. fileciteturn1file4L1-L8

For each stakeholder, students should include:

- who they are
- their role
- how they interact with the current system
- what they need from the new system
- how often they are likely to use it

A simple table works well:

| Stakeholder | Role | Current interaction | Need from new system |
|---|---|---|---|
| Head of Department | Oversees room use | Resolves clashes manually | Wants quick overview and fewer conflicts |
| Teachers | Make bookings | Use paper sheet or email | Want fast booking and editing |
| Students | Check or request access | Ask staff directly | Need clear confirmation of sessions |

OCR’s project setting guidance says weak stakeholder use leads to shallow discussion and weaker success criteria, while strong stakeholder input improves analysis, design and evaluation. ([ocr.org.uk](https://www.ocr.org.uk/Images/324587-project-setting-guidance.pdf?utm_source=chatgpt.com))

## Step 4: Research similar existing solutions

The attached guide says students should research other software or comparable solutions, ideally at least several, and analyse their strengths, weaknesses and relevance to the proposed system. fileciteturn1file2L12-L20

This means students should not just say “I looked at Google Calendar.” They should write analytically.

A good subsection for each existing solution is:

**Solution researched:** Google Calendar  
**Relevant features:** date/time selection, colour-coded events, recurring bookings  
**Strengths:** familiar interface, clear calendar view, fast entry  
**Weaknesses:** too many features for a simple departmental system, permissions are more complex than needed  
**How this informs my project:** I will use a calendar-style weekly view and colour-code booking types, but I will keep permissions simpler

Students should include screenshots if useful, but the key mark-winning part is the commentary: what was learned and how it changed the proposed solution. The attached guide explicitly says good performance in this section comes from researching similar solutions in depth and justifying the chosen approach. fileciteturn1file2L17-L20

## Step 5: Gather primary research from stakeholders

The attached guide recommends using a range of research methods, especially **meetings/interviews** and **surveys**, and explains that stakeholder discussions are needed to link the problem to the requirements specification. fileciteturn1file4L5-L10 Meetings are described as especially valuable for understanding the problem, while surveys are useful when many people need to answer the same questions. fileciteturn1file1L1-L13

A sensible pattern is:

- interview the main stakeholder first
- then use a short survey for wider users
- then follow up unclear points

Students should summarise findings, not dump raw transcripts. OCR’s 2017 report said many candidates wasted time typing full interviews and that a **summary of key points** is sufficient. ([ocr.org.uk](https://www.ocr.org.uk/Images/417078-examiners-report-june.pdf?utm_source=chatgpt.com))

A good write-up looks like this:

**Method used:** Interview with Head of Department  
**Reason:** Main decision-maker and frequent user of booking information  
**Key findings:**  
- clashes are the biggest problem  
- staff need instant confirmation of bookings  
- old bookings should be searchable  
- the interface must be simple because not all users are confident with complex software  

Then add:  
**Impact on solution:**  
“This led to the inclusion of conflict checking, a searchable booking history, and a simple form-based interface.”

## Step 6: Separate qualitative and quantitative findings

The attached guide distinguishes between **qualitative** and **quantitative** research and explains that both may be useful. fileciteturn1file2L8-L16

Students can use this to improve structure:

**Qualitative findings**  
These are opinions, comments, suggestions, frustrations, preferences.

**Quantitative findings**  
These are counts, percentages, ratings, yes/no results.

For example:

- 9 out of 12 staff said double-booking is a weekly issue
- 10 out of 12 said they want a weekly calendar view
- comments showed that users value speed and simplicity more than advanced reporting

This helps justify requirements later.

## Step 7: Turn research into numbered requirements

This is the most important part of the Analysis.

The attached guide says the **requirements specification defines the rest of the project**, and each requirement should be supported by research evidence. It also recommends numbering each requirement so it can be referenced later. fileciteturn1file1L8-L16

The strongest format is a numbered requirements table with columns like:

- requirement number
- requirement
- who wants it
- evidence/research source
- justification
- measurable success criteria

For example:

**R1. Secure login for staff**  
Stakeholder: Head of Department  
Evidence: interview, existing-solution research  
Justification: booking data must only be edited by authorised users  
Success criteria: only valid username/password combinations are accepted; invalid login shows error message; password field is masked

**R2. Prevent booking clashes**  
Stakeholder: Teachers  
Evidence: staff survey and interview  
Justification: double-bookings are the main problem in the current system  
Success criteria: if a room/time is already booked, the system blocks the booking and displays a warning

The attached guide explicitly recommends starting with main requirements, breaking them into smaller ones, linking them to research, and making the success criteria measurable. fileciteturn1file3L24-L31

## Step 8: Make success criteria measurable

This is where many students lose quality.

OCR’s planning blog says success criteria should be **clear and measurable**, and vague objectives weaken the project. ([ocr.org.uk](https://www.ocr.org.uk/blog/a-level-computer-science-top-tips-for-planning-the-nea-programming-project/)) OCR’s 2017 report also noted that vague objectives such as “easy to use” or “loads quickly” caused students to lose marks in analysis and later sections too. ([ocr.org.uk](https://www.ocr.org.uk/Images/417078-examiners-report-june.pdf?utm_source=chatgpt.com)) The attached guide gives the same advice and warns against vague statements. fileciteturn1file3L20-L31

Bad success criteria:
- the program should be user friendly
- the system should work well
- the colours should look nice

Better success criteria:
- a new booking can be entered in under 30 seconds by a trained user
- the system prevents duplicate bookings for the same room, date and time
- the system can search bookings by teacher surname in no more than 3 clicks
- the interface uses the department’s agreed colour scheme and is approved by the stakeholder

Students should be able to test every success criterion later.

## Step 9: State the limitations of the proposed solution

OCR expects students to explain limitations of the proposed solution. ([ocr.org.uk](https://www.ocr.org.uk/Images/257212-crossover-reference-guide.pdf?utm_source=chatgpt.com)) The attached guide says this is where students explain what will not be implemented and justify why. fileciteturn1file3L31-L31 fileciteturn0file0L40-L40

Examples:

- the project will not synchronise with Microsoft Outlook
- the project will only run on Windows devices in school
- it will support one department rather than the whole school
- it will use local storage rather than a cloud database

The reason must sound professional and realistic, not “I don’t know how.” The guide explicitly warns that “too hard” is not a good justification on its own. fileciteturn0file0L40-L40

## Step 10: Include hardware and software requirements if relevant

The attached guide says students should identify any additional hardware or software needed to run the solution successfully, especially if it affects the user or deployment. fileciteturn0file0L41-L41

This does not need a full PC spec unless relevant. Usually this section should mention only things that matter, such as:

- Windows 11
- Python 3.12
- SQLite
- internet connection if API-based
- webcam, barcode scanner, sensors, etc if needed

## Step 11: Write commentary, not just evidence

The attached guide says commentary should explain the journey from initial idea through research and stakeholder discussion to the final chosen solution, and it should be concise. fileciteturn0file0L42-L42

That means students should keep asking:

- What did I find?
- Why does it matter?
- How did it affect my decisions?

A strong sentence looks like this:

“Although Google Calendar offers recurring events, stakeholder feedback suggested that this would add unnecessary complexity at this stage, so recurring bookings will not be part of the first version.”

That is much better than simply listing a feature.

## Step 12: End the Analysis with a clean summary

Finish with a short paragraph that says, in effect:

- the problem has been defined
- stakeholders and research have informed the solution
- the requirements and success criteria are now clear
- these will drive the design and testing

This creates a strong bridge into the Design section.

## A recommended structure students can follow

1. Problem definition  
2. Why the problem is suited to a computational approach  
3. Stakeholders  
4. Research into existing solutions  
5. Primary research with stakeholders  
6. Summary of findings  
7. Numbered requirements specification  
8. Measurable success criteria  
9. Limitations of the proposed solution  
10. Hardware/software requirements  
11. Analysis summary

## Common mistakes to avoid

The biggest errors are usually these:

- writing vague aims instead of measurable requirements
- describing research without explaining its impact
- using too little stakeholder input
- copying long interview transcripts instead of summarising findings
- listing features without justification
- writing generic claims like “computers are faster”
- turning the Analysis into an early Design section

OCR has specifically noted that limited stakeholder interaction can restrict access to higher mark bands, and that over-reliance on AI in the Analysis can do the same because the section should reflect genuine stakeholder engagement. ([ocr.org.uk](https://www.ocr.org.uk/blog/guidance-and-support-for-the-use-of-ai-in-a-level-computer-science-nea/))

## A very short model paragraph

Here is the sort of tone students should aim for:

“The current room-booking process is paper-based and leads to frequent clashes, lost information and wasted staff time. This problem is suitable for a computational solution because the system must store booking data, validate entries, search records and prevent clashes automatically. Interviews with the Head of Department and a survey of teaching staff showed that the most important requirements are fast booking entry, clear confirmation messages and conflict detection. Research into Google Calendar, Microsoft Bookings and two school-facing booking systems showed that calendar-style displays and simple form-based entry are effective, but overly complex permissions are unnecessary for this project. As a result, the proposed solution will focus on a single-department desktop system with secure staff login, clash prevention, searchable records and a simple weekly view.”
