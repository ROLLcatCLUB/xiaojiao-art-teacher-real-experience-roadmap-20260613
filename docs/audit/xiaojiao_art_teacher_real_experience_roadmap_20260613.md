# Xiaojiao Art Teacher Real Experience Roadmap

```text
record_id=XIAOJIAO_ART_TEACHER_REAL_EXPERIENCE_ROADMAP_20260613
decision=ACCEPT_AS_RUNTIME_EXPERIENCE_ROUTE_REFERENCE
next_stage=1007J_ART_TEACHER_PRODUCT_EXPERIENCE_REVIEW_AND_LIGHT_RECORDING_PLANNING
runtime_preview_target=1007K_ART_TEACHER_LOCAL_CLICKABLE_RUNTIME_PREVIEW
```

## Current Position

```text
1006 = minimum runtime foundation reached teacher_review_gate
1007A-H = art teacher business pack vertical slice dry-run accepted
1007I = static productized preview accepted with SHA record sync fix
```

## Core Judgement

Do not keep expanding horizontally. The next product milestone should be one art teacher daily work vertical slice that can be clicked, then can generate real sandbox candidates, then can be used continuously by the owner.

## Experience Timeline

| Level | Target | Estimate | Meaning |
| --- | --- | ---: | --- |
| A | Open and view / clickthrough | 1-2 days | Local page, today entry, lesson focus, handout candidate patch preview, teacher review stop. |
| B | Operable state changes | 3-5 days | JSON/localStorage/light in-memory Work State; confirm/defer/update suggestions/review queue. |
| C | Real candidate generation | 7-10 days | Provider sandbox for handout and lesson-section revision candidates, still teacher review before apply. |
| D | Owner continuous minimum usable version | 2-3 weeks | Today work, lesson focus, handout/rubric candidates, light process recording, work record, local persistence. |
| E | Small teacher trial readiness | 4-8 weeks | Controlled stability, privacy, onboarding, support, and feedback loop. |

## Recommended Route

```text
1007J_PRODUCT_EXPERIENCE_REVIEW_AND_LIGHT_RECORDING_PLANNING
?
1007K_LOCAL_CLICKABLE_RUNTIME_PREVIEW
?
1008A_PROVIDER_SANDBOX_PLANNING
?
1008B_HANDOUT_AND_SECTION_REVISION_PROVIDER_SANDBOX
?
1009A_MINIMAL_RESOURCE_CONTEXT_INTEGRATION
?
1010A_OWNER_TRIAL_MINIMUM_USABLE_VERSION
```

## Lines To Hold

```text
classroom_teaching_studio
public_display_surface
teacher_control_surface
student_side_runtime
student_evaluation_analysis_board
full_resource_library
grid_studio_complex_workspace
school_admin_backend
```

## Boundary For 1007K

1007K can be locally clickable and stateful, but should still avoid provider/model, real database, memory, Feishu, formal export, production frontend runtime modification, and formal business apply unless explicitly authorized.
