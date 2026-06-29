# Rhythm Game Beatmap Difficulty Review Dataset

This repository contains anonymized and normalized sample materials for a rhythm game beatmap difficulty review task.

The dataset is prepared for evaluating whether the current difficulty levels of 48 four-key falling-note beatmaps are consistent with machine-readable chart features,playtest results,QA review notes,and community feedback.

## Files

- `beatmap_features.csv`  
  An anonymized feature table for 48 four-key falling-note beatmaps. Each row corresponds to one beatmap and includes fields such as song_id,title,duration,total_notes,avg_nps,peak_nps,jack density,chord ratio,SV change count,column distribution,stamina strain,reading complexity,and current level.

- `playtest_results_by_rank.csv`  
  An anonymized playtest summary table grouped by beatmap and player rank. It includes pass rate,average accuracy,max combo ratio,and average miss count for Bronze,Silver,Gold,and Diamond player groups.

- `qa_review_notes.csv`  
  An anonymized QA review table containing reviewer notes,severity labels,and suggested actions for selected beatmaps.

- `community_feedback_summary.md`  
  A curated and anonymized feedback summary containing representative comments about beatmap difficulty mismatches. The content has been grouped by beatmap and does not include original user identifiers beyond anonymized display names.

## Notes

The CSV and markdown files are anonymized sample materials prepared for a beatmap difficulty review scenario. They are intended for structured analysis and model evaluation.

These files should not be described as externally verifiable raw production logs or complete public community archives.

When using this repository,please cite the file name and the relevant row,field,section,or quoted feedback item where applicable.
When using this repository,please cite the file name and the relevant row,field,section,or quoted feedback item where applicable.
