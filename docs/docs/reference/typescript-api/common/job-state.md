---
title: "JobState"
weight: 10
date: 2023-07-21T07:17:02.461Z
showtoc: true
generated: true
---
<!-- This file was generated from the Vendure source. Do not modify. Instead, re-run the "docs:build" script -->
import MemberInfo from '@site/src/components/MemberInfo';
import GenerationInfo from '@site/src/components/GenerationInfo';
import MemberDescription from '@site/src/components/MemberDescription';


## JobState

<GenerationInfo sourceFile="packages/common/src/generated-types.ts" sourceLine="2097" packageName="@vendure/common" />

The state of a Job in the JobQueue

```ts title="Signature"
enum JobState {
  CANCELLED = 'CANCELLED'
  COMPLETED = 'COMPLETED'
  FAILED = 'FAILED'
  PENDING = 'PENDING'
  RETRYING = 'RETRYING'
  RUNNING = 'RUNNING'
}
```