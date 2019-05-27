# Containerize Workflow

Johannes' Workflow relies on software installed in multiple different locations (CloudImage, Nemo, Jülich) and the `module load` system of adding paths to software binaries to the respective PATH variables.
This project aims to replace this solution with container images, which are static, self-contained and have a formal recipe for assembling them.
