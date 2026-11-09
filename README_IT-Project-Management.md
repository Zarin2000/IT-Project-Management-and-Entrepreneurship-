# IT Project Management and Entrepreneurship (CSE495)

Coursework from my BSc in Computer Science and Engineering at East West University, Dhaka. The repo has two parts: a group mini project I worked on in Fall 2023, and an individual scheduling assignment from the same course.

## Mini project: Intelligent System for Enhancing Artistic Expression

The full title is "Implementation and Deployment Project of Intelligent System for Enhancing Artistic Expression". As a planning exercise, we worked out how to deliver an app where people draw an object on a digital canvas, a machine learning model recognises what they drew, and the app scores how accurate the drawing is and gives feedback. It was aimed at children and anyone practising drawing. Our team of five wrote the project plan end to end, and I was the Project Owner in the charter.

What the plan covers:

- **Charter, stakeholders and risks.** A project charter, a stakeholder analysis that rates each group's influence and support and sets an engagement strategy, and a risk table with probability, severity and mitigation for each risk. The risks include model accuracy, bias in the model, getting a drawing dataset, computing limits, user engagement and privacy.
- **Schedule and resources.** A work breakdown with 14 activities between a start and end milestone, a Gantt chart built in Microsoft Project, a resource sheet, and a fix for resource over-allocation. The plan runs 37 weeks.
- **Budget.** A total cost of 1,030,500 BDT covering labour, consultants, testing and a database server.
- **Cost-benefit analysis.** Income comes from app store downloads and ad revenue, with 3% of the investment per year set aside for maintenance.

### Cost-benefit results

| Measure | Result |
|---------|--------|
| NPV at 12% | about 2.38 million BDT |
| Benefit-cost ratio | 2.97 |
| IRR | about 32% |
| Payback period | 5.29 years |

The assumptions were a one-year build, then ten years of benefits, a 12% discount rate, 75 BDT per download and 20 BDT per ad, with both growing 50% a year. The spreadsheet model counts downloads and ad revenue only. The report also lists paper savings and CO₂ reductions as benefits, but those aren't in the NPV, BCR or IRR figures.

## Individual assignments

- **Critical path method and Gantt chart** (submitted October 2023). I built the Gantt chart in software and by hand, found the critical path and the slack on non-critical tasks, looked at which tasks could be crashed, and allocated resources. The project duration came to 639 days. Tasks 8, 9 and 15 are off the critical path, with 380 days of combined slack.
- **NPV, BCR and IRR exercise.** A spreadsheet that discounts a set of costs and incomes at 12% and 15%. At 12% the NPV is about -46.8, the BCR is 0.94 and the IRR is about 10.2%. At 15% the NPV is about -108.0 and the BCR is 0.84. With a negative NPV and a BCR below 1 at both rates, the project doesn't pay off.

## What's in the repo

```
Assignment(NPV, BCR, IRR).xlsx                       discounting exercise
Project1(Critical Path Method and Gantt Chart).pdf   6-page CPM assignment
Project1.mpp                                         Microsoft Project file
Mini Project/
├── Project-Charter.pdf          charter, stakeholder analysis, risk analysis (10 pages)
├── CSE495_Project2ndPhase.pdf   Gantt, resources, costs, cash flow (11 pages)
├── Project495_Report .pdf       full report (21 pages)
├── Project495_report.docx       editable version of the report
├── Project.pptx                 18-slide presentation
├── project.xlsx                 cost-benefit model
└── Project1.mpp                 Microsoft Project plan
```

The `.mpp` files need Microsoft Project to open. The spreadsheets keep their formulas, so you can change an assumption and watch the results move.

## Please don't copy

This is my own coursework, shared for my portfolio. Please don't submit it as yours. If it helps your thinking, cite it.

## Contact

- GitHub: [Zarin2000](https://github.com/Zarin2000)
- LinkedIn: [Zarin Tasnim Nuzhat](https://www.linkedin.com/in/zarin-tasnim-nuzhat-829007202)
- ORCID: [0009-0006-3469-1876](https://orcid.org/0009-0006-3469-1876)
