## My completed work: Part I (People)

GitHub can't preview the completed notebook because the file is 17.7 MB (it keeps every output and figure). Open it with one of these links instead:

| | Link |
|---|---|
| **View and run in Google Colab (recommended, with all outputs)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kdoo_hBNqEx4sDjPVfqE-KyqGLuLTann) |
| Open this repository's copy in Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Bouchra159/flood-monitoring/blob/main/Copie_de_CCAI_Tutorial_on_Flood_Monitoring_Part_I_People.ipynb) |
| Read-only view with all outputs (nbviewer) | [View on nbviewer](https://nbviewer.org/github/Bouchra159/flood-monitoring/blob/main/Copie_de_CCAI_Tutorial_on_Flood_Monitoring_Part_I_People.ipynb) |
| Notebook file in this repository | [Copie_de_CCAI_Tutorial_on_Flood_Monitoring_Part_I_People.ipynb](Copie_de_CCAI_Tutorial_on_Flood_Monitoring_Part_I_People.ipynb) |

**What the completed notebook adds to the tutorial**

| Area | Content |
|---|---|
| Full run | Every cell run end to end on a T4 GPU, with carbon tracking (CodeCarbon) |
| Fixes | Corrected Sentinel-1 normalisation text, metric names and out-of-date comments; explained why the test MSE is lower than the training loss; found and fixed undeclared `-9999` nodata values in the DEM tiles |
| Exercise solutions (S1–S10) | Precision–recall threshold sweep, error analysis by building density and by tile, early stopping and best checkpoint, a residual U-Net, Sentinel-2 + Sentinel-1 + DEM fusion, a spatial-block holdout repeated over 3 seeds, rotation/flip/CutMix augmentation, a GPU vs. CPU energy comparison, and a summary table of all experiments |
| Written answers | Every reflection question, the decision-product exercise (built-up area near water, and which stakeholders need it in what form), and the responsible-use reflection |
| Key results | Adding SAR and DEM gave the best F1 (0.64) and IoU (0.48) at the lowest energy (2.6 Wh); training on the CPU would use about 23x more energy per epoch than on the GPU |

---

# Sea Water Flood Risk Assessment in Egypt using Deep Learning, Sentinel-1 & 2, and Copernicus DEM
Floods in coastal areas can be extremely destructive natural hazards resulting in societal and economical damage. In this tutorial, explore how to predict building and population density to understand the potential impact from a flooding event.

Authors:
* Casper Fibaek, European Space Agency Φ-lab, Casper.Fibaek@esa.int
* Andreas Luyts, European Space Agency Φ-lab, Andreas.Luyts@ext.esa.int
* Nirdesh Kumar Sharma, [EarthSense Labs](https://earthsenselabs.com/), nirdesh@earthsenselabs.com

Originally presented at Climate Change AI Summer School 2023, revised for the Summer School 2026

## Access this tutorial

We recommend executing these notebooks in a Colab environment to gain access to GPUs and to manage all necessary dependencies.

Part I: <a target="_blank" href="https://colab.research.google.com/github/climatechange-ai-tutorials/flood-monitoring/blob/main/CCAI_Tutorial_on_Flood_Monitoring_Part_I_People.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Part II: <a target="_blank" href="https://colab.research.google.com/github/climatechange-ai-tutorials/flood-monitoring/blob/main/CCAI_Tutorial_on_Flood_Monitoring_Part_II_Water.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Estimated time to execute end-to-end: 30 minutes

## Contribute to this tutorial

Please refer to these [GitHub instructions](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) to open a pull request via the "fork and pull request" workflow. 

Pull requests will be reviewed by members of the Climate Change AI Tutorials team for relevance, accuracy, and conciseness.

## Climate Change AI Tutorials
Check out the [tutorials page](https://www.climatechange.ai/tutorials?) on our website for a full list of tutorials demonstrating how AI can be used to tackle problems related to climate change.

## License
Usage of this tutorial is subject to the MIT License.

## Cite

### Plain Text
Fibaek, C., Luyts, A., Sharma, N. (2026). Sea Water Flood Risk Assessment in Egypt using Deep Learning, Sentinel-1 & 2, and Copernicus DEM [Tutorial]. In Climate Change AI Summer School 2026. Climate Change AI. https://doi.org/10.5281/zenodo.21982751

### BibTeX

```
@misc{fibaek2026sea,
  title={Sea Water Flood Risk Assessment in Egypt using Deep Learning, Sentinel-1 & 2, and Copernicus DEM},
  author={Fibaek, Casper and Luyts, Andreas and Sharma, Nirdesh},
  year={2026},
  howpublished={\url{https://github.com/climatechange-ai-tutorials/flood-monitoring}},
  organization={Climate Change AI},
  type={Tutorial},
  doi={https://doi.org/10.5281/zenodo.21982751},
  booktitle={Climate Change AI Summer School 2026}
}
```
