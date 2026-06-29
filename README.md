# Rhythm Game Beatmap Difficulty Review Dataset

This repository contains anonymized and normalized materials for a rhythm game beatmap difficulty review task.

The dataset is prepared for evaluating whether the current difficulty levels of 48 four-key falling-note beatmaps are consistent with machine-readable chart features, playtest results,QA review notes,and community feedback.

## Files

* `osu_star_rating.html`
  HTML snapshot of the osu!wiki page about Star Rating. It describes the general concept of star rating,difficulty color mapping,and rating thresholds.
  Source:https://osu.ppy.sh/wiki/en/Beatmap/Star_rating

* `stepmania_difficulty_ordinal_regression.pdf`
  PDF paper titled `Ordinal Regression for Difficulty Estimation of StepMania Levels`. It discusses StepMania difficulty estimation,feature extraction,ordinal regression models,and evaluation results.
  Source:https://arxiv.org/pdf/2301.09485

* `osu_mania_ranking_criteria.html`
  HTML snapshot of the osu!mania ranking criteria page. It describes osu!mania-specific ranking rules,difficulty naming,key modes,rhythm rules,patterns,and difficulty expectations.
  Source:https://osu.ppy.sh/wiki/en/Ranking_criteria/osu%21mania

* `osu_file_format.html`
  HTML snapshot of the osu!wiki page about the `.osu` file format. It describes sections such as General,Metadata,Difficulty,TimingPoints,and HitObjects.
  Source:https://osu.ppy.sh/wiki/en/Client/File_formats/osu_(file_format)

* `beatmap_features.csv`
  An anonymized feature table for 48 four-key falling-note beatmaps. Each row corresponds to one beatmap and includes fields such as song_id,title,duration,total_notes,avg_nps,peak_nps,jack density,chord ratio,SV change count,column distribution,stamina strain,reading complexity,and current level.

* `playtest_results_by_rank.csv`
  An anonymized playtest summary table grouped by beatmap and player rank. It includes pass rate,average accuracy,max combo ratio,and average miss count for Bronze,Silver,Gold,and Diamond player groups.

* `qa_review_notes.csv`
  An anonymized QA review table containing reviewer notes,severity labels,and suggested actions for selected beatmaps.

* `community_feedback_summary.md`
  A curated and anonymized feedback summary containing representative comments about beatmap difficulty mismatches. The content has been grouped by beatmap and does not include original user identifiers beyond anonymized display names.

## Notes

The public reference files are provided with their original source links.

The CSV and markdown data files are anonymized sample materials prepared for a beatmap difficulty review scenario. They are intended for structured analysis and model evaluation. They should not be described as externally verifiable raw production logs or complete public community archives.

When using this repository,please cite the file name and the relevant row,field,section,or quoted feedback item where applicable.
