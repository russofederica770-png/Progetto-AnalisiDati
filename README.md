# Progetto-AnalisiDati
I developed, together with other colleagues from my degree course, a Python project for the Numerical Methods for Data Analysis course focused on price updating and uncertainty quantification in transport pricing datasets. The project was centered on the analysis of the dataset provided during the course and on the use of ISTAT indices to build a historical price updating function.

We then focused on quantifying the uncertainty introduced by the updating process, initially applying a strategy based exclusively on ISTAT indices. The analysis highlighted several structural limitations of the method, mainly due to temporal asynchrony and the presence of dynamic and non-linear variables that ISTAT indices tend to smooth out.

For this reason, we implemented two corrective strategies: the first aimed at mitigating temporal asynchrony, while the second considered the dynamic variables previously excluded. The obtained results showed an improvement in the trend of the estimates, together with a reduction in uncertainty and model error.

Technologies used: Python, Pandas, NumPy, Matplotlib and Jupyter Notebook.
