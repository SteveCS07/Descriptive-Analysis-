# Descriptive-Analysis-
{
  "metadata": {
    "language_info": {
      "codemirror_mode": {
        "name": "python",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.8"
    },
    "kernelspec": {
      "name": "python",
      "display_name": "Python (Pyodide)",
      "language": "python"
    }
  },
  "nbformat_minor": 4,
  "nbformat": 4,
  "cells": [
    {
      "cell_type": "code",
      "source": "import pandas as pd \nimport csv\nimport numpy as np\nimport matplotlib.pyplot as plt",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "url = \"https://internships-data.s3.ap-south-1.amazonaws.com/interns+data/Enrollments_28092022.csv\\\\n\",\ndf = pd.read_csv(url),\nprint(df)",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.shape",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.count()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.dtypes ",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "dfplot = df.plot(kind =\"hist\", ec=\"black\")",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.mean()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.median()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.mode",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.max()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.min()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "df.describe()",
      "metadata": {
        "trusted": true
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "plt.pie(sizes, labels=labels)",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": "plt.boxplot(figsize=(3,3))",
      "metadata": {},
      "execution_count": null,
      "outputs": []
    }
  ]
}
