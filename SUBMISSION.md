# MC2 FS26 Submission Manifest

Student: Christof Weickhardt
Country: Canada
Semester: FS26

## Submit These Files

- notebooks/01_augmentation_lake_louise.ipynb
- notebooks/02_pattern_detection_empress_canny.ipynb
- notebooks/03_segmentation_empress_windows.ipynb
- html/01_augmentation_lake_louise.html
- html/02_pattern_detection_empress_canny.html
- html/03_segmentation_empress_windows.html
- notebooks/images/IMG_1020.jpeg
- notebooks/images/C0D2037D-3959-4F04-B6D2-936473639D34_1_105_c.jpeg
- notebooks/annotations/empress_task3_holdout_polygons.json
- notebooks/annotations/empress_task3_full_pane_polygons.json
- pyproject.toml
- uv.lock

## Reproducibility

Run from the repository root:

```bash
uv run --locked jupyter nbconvert --to notebook --execute --inplace notebooks/01_augmentation_lake_louise.ipynb notebooks/02_pattern_detection_empress_canny.ipynb notebooks/03_segmentation_empress_windows.ipynb
uv run --locked jupyter nbconvert --to html --embed-images --output-dir html notebooks/01_augmentation_lake_louise.ipynb notebooks/02_pattern_detection_empress_canny.ipynb notebooks/03_segmentation_empress_windows.ipynb
```

Do not submit local environments, temporary extraction files, generated review reports, or analysis scratch files.
