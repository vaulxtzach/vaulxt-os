Phase 0 / Phase 1 Schema

Platform Foundation
- Workspace
- User
- WorkspaceUser
- SystemSetting
- FeatureFlag
- ModuleDefinition
- InstalledModule
- ProductPackage
- WorkspacePackage
- AuditLog
- ExceptionEvent
- ReviewQueueItem
- Task

Intake Foundation
- UploadedFile
- Dataset
- DatasetVersion
- FieldMapping
- RawLeadRow

Lead Core
- Lead
- DncSuppression
- LeadMergeEvent
- LeadScoreSnapshot

Scoring Foundation
- ScoreModel
- ScoreRule

Purpose
This schema cut supports:
- protected shell
- feature/module/package control
- audit/review foundation
- dataset upload pipeline
- field mapping
- normalization
- DNC suppression
- canonical lead creation
- baseline scoring
