graph TD;
  A[Employee Identifies Concern] --> B[Decide to Report Concern]
  B --> C[Choose Reporting Channel]
  
  C --> D[Report to Line Manager or HR]
  C --> E[Report to Director - Serious Cases]
  C --> F[Report to External Bodies - Regulators, ESFA, etc.]

  D --> G[Fieri Receives the Disclosure]
  E --> G
  F --> J[Escalation to External Bodies]

  G --> H[Acknowledge Receipt - Within 5 Days]
  H --> I[Initial Assessment - Within 10 Days]
  
  I -->|Valid Concern| K[Investigation - Within 30 Days]
  I -->|Not Valid| L[Inform Whistleblower & Advise Next Steps]

  K --> M[Independent Inquiry Conducted]
  M -->|Extra Time Needed?| N[Inform Whistleblower & Provide Update] --> O[Outcome & Feedback]

  O --> P[Actions Taken & Decision Logged]
  O --> Q[Confidential Feedback Given]

  P --> R[Appeals & Escalation]
  Q --> R
  R --> S[Internal Review]
  R --> T[External Reporting - Regulators & Legal Authorities]

  S --> U[Protection & Support for Whistleblowers]
  T --> U

  U --> V[Confidentiality Maintained]
  U --> W[Protection from Retaliation]
  U --> X[HR & Advisory Support]

  V --> Y[Tracking & Monitoring]
  W --> Y
  X --> Y

  Y --> Z[Secure Case Logging & Policy Review]
  Y --> AA[Annual Review & Trend Analysis]
