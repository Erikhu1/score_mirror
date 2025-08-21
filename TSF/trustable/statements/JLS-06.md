---
level: 1.1
normative: true
evidence:
  type: "check_artifact_exists"
  configuration:
    check_amalgamation: "test"
    codeql: "include"
    dependency_review: "include"
    labeler: "exclude"
    test_trudag_extensions: "include"
    ubuntu: "324"
---

Changes to the code (main branch) are applied only after code review and passing of all pipelines.
