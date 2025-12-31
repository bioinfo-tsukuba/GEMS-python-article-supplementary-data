# Supplementary captions

**Supplementary Table ST1 — Execution summary (cell-culture run).**
EnglishExecution summary for all jobs in the cell-culture run. Columns: reservation_time (time scheduling was performed; tentative under dynamic scheduling), optimal_start_time, scheduled_time, execution_start_time, processing_time, experiment_operation, experiment_uuid.

**Supplementary Table ST2 — State-transition history (TSV).**
State-transition history across all experiments (TSV). Each row records the state reached at each discrete step; columns list individual experiments, corresponding to Supplementary Video S3.

**Supplementary Video S1 — Operation-level Gantt animation.**
Gantt animation grouped by operation type (e.g., imaging, passaging, medium change), showing reservation, optimal, scheduled, and actual start times across experiments. (Colour-mixing has no timeline.)

**Supplementary Video S2 — Experiment-level Gantt animation.**
Gantt animation grouped by experiment for the cell-culture run, showing reservation, optimal, scheduled, and actual start times over wall-clock time. (The colour-mixing experiment executed immediately and has no timeline.)

**Supplementary Video S3 — State-transition animation.**
Animation of state progression over discrete steps, independent of wall-clock time; table counterpart is Supplementary Table ST2.

**Supplementary Figure SF1 — State timelines reconstructed from GEMS logs.**
State timelines for all experiments in the cell-culture run, reconstructed from the state-transition history (Supplementary Table ST2). Each row corresponds to one experiment; coloured blocks indicate the DFA state at each discrete orchestration step, and boundaries between blocks correspond to state transitions. This static summary complements the state-transition animation (Supplementary Video S3) and the execution timelines shown as Gantt animations (Supplementary Videos S1–S2), with job-level timestamps provided in Supplementary Table ST1.

## Legend for operation abbreviations used in S1, S2:
- iPSMediumChange = iPS-MC
- iPSPassage = iPS-P
- iPSPlateCoating = iPS-PC
- iPSGetImage = iPS-IMG
- iPSSampling = iPS-SMP
- iPSWaiting = iPS-W
- HEKPassage = HEK-P
- HEKGetImage = HEK-IMG
- HEKSampling = HEK-SMP
- HEKWaiting = HEK-W
