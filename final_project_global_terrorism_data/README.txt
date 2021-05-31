The Tableau workbook contains the following visualizations, found in final_project_dashboard.twb and final_project_dashboard.twbx:
	- Map of the world colored based on number of attacks with a time scale filter (Figure 1)
	- Multi-line graph of number of attacks per attack type over time (not used in final dashboard) (Figure 3)
	- Bar graph of each attack type and the number of people killed and wounded by those attacks - (seen in Figure 4 - dashboard)
	- List of attack types associated with colors, used in draft dashboard to allow filtering based on attack type (not used in final dashboard, not used in paper)
	- Bar chart of the 15 most active terrorist groups by the number of attacks the committed (seen in Figure 4 - dashboard)
	- Draft dashboard combining the first four sheets. All vizs act as filters. It was determined that the two attack type graphs were redundant. (not used in paper)
	- Final dashboard incorporating the terrorist groups, map, and attack type bar graph. All vizs act as filters. (Figure 4)
		- This dashboard is available on Tableau Public at https://public.tableau.com/profile/lauren6941#!/vizhome/GlobalTerrorismDashboard_16187201999550/Dashboard-Final

To re-create the Python visualization of the number of attacks per region over time, use the FinalProjEDA.ipynb Jupyter Notebook.
	This notebook includes code for cursory exploratory data analysis of the terrorism dataset, as well as matplotlib code for the vizualization.
	Running the notebook will reproduce Figure 2 from the paper.
	The notebook requires Python 3, and the following libraries must be installed:
		-pandas
		-matplotlib
		-seaborn
