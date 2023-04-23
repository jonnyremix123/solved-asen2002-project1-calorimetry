Download Link: https://assignmentchef.com/product/solved-asen2002-project1-calorimetry
<br>
<em>Use temperature measurements, the first law of thermodynamics, error propagation, and least squares extrapolation to determine the specific heat of a sample material. Assess the associated errors and determine the possible material from which the sample is made. </em>

<h1>INSTRUCTIONS</h1>

This project is an individual assignment. Please watch a detailed review of the Calorimeter methods here: <u>https://www.youtube.com/playlist?list=PLfIpWHYDHoWzrF3dRX6wrAOZb8pkifLgx</u>

From this information, you should write your “Methods” section of the report. <em>The data files required to carry out your analysis will be posted on the Canvas website after the laboratory session.</em>We will assign you a specific sample (1 of 4) to solve for in this lab. Use the posted data to determine the sample’s material type, selecting from the posted candidate materials properties. You will do this using the methodology outlined below and presented in class incorporating error propagation and least squares linear fitting. Compile your findings into a report (outlined below). Your MATLAB code must be submitted in a zipped folder with all required files for the code to compile. Submit the report and associated MATLAB code to Canvas before the due date.

<h1>REPORT DELIVERABLE</h1>

<ul>

 <li>Report must have the following sections: 1) Abstract 2) Introduction 3) Experimental method 4) Results 5) Discussion 6) Conclusion 7) References and 8) Appendix containing your code flow chart and an analytical derivation of error propagated for Eq. (1). Note that your flow chart may be written by hand or using graphical software, but it must be in the proper symbol format and detail. Your analytical derivation of the error associated with Eq. (1) may be typed or handwritten.</li>

 <li>The report must be written in the AIAA format. You should use the technical writing principles discussed in class. You will be assessed on your writing skills in this project.</li>

 <li>Your report may be <strong>no longer than 4 pages in length</strong>, excluding the References and Appendix (i.e. your code flow chart and analytical solution of error propagation).</li>

</ul>

<strong> </strong>

<strong>Calorimetry analysis to be included in your report: </strong>

<ol>

 <li>Include a derivation of Eq. (1) below in your report using the First Law of Thermodynamics.</li>

 <li>Estimate the specific heat of your sample from Eq. (1) below and identify the material from which the sample may have been made. Information on candidate materials will be provided.</li>

 <li>Providing an error estimate for your computed values and relate whether the accepted value of specific heat of the material you propose the sample may be made from falls within the error estimate. If the deviation was significant, where the accepted value lies outside the error bar, how would parameters used in your calculation from Eq. (1) below have to change to account for the observed bias? Provide physical reasoning behind your assessment.</li>

</ol>

<em><u>Calorimetry background</u></em>

Calorimetry is a basic technique for measuring thermodynamic quantities, especially those involving heat transfer, i.e., specific heats, heat of fusion, heat of vaporization, and heat of chemical reactions.  It is one of the oldest experimental methods in thermodynamics. Benjamin Thompson used a calorimeter in 1798 to show that work could be converted to heat (thermal energy), and James Joule conducted elegant experiments in the 1840s to measure the mechanical equivalent of heat (thermal energy).  People who count “calories” can look up the energy value of various foods in their diet, e.g., three Chips Ahoy cookies (~32 grams) supply 169 Calories (kcal) of energy.  We know this because someone, in this case Nabisco, Inc., conducted calorimetry experiments.

Heat transfer between the sample of a given temperature and the calorimeter of a different given temperature takes place. The basic set up of a calorimeter is shown in Fig. 1. Assuming the sample combined with the calorimeter are an adiabatic system, one can show that

<h1><em>C<sub>s av</sub></em>, =<em>mC T T<sup>c c av</sup>m T T<sub>s</sub></em><sup>,</sup>( <sub>1</sub>(-<sup>2 </sup>–<sub>2</sub>) <sup>0</sup>)                                                             (1)</h1>

where <em>C<sub>s</sub></em><sub>,<em>av</em></sub> = specific heat of the sample, <em>C<sub>c</sub></em><sub>,<em>av</em></sub> = specific heat of the calorimeter, <em>T</em><sub>0</sub> = initial temperature of the calorimeter, <em>T</em><sub>1</sub> = initial temperature of the sample, <em>T</em><sub>2</sub> = final temperature of the calorimeter and sample at equilibrium, <em>m<sub>c</sub> </em>= mass of the calorimeter, and <em>m<sub>s</sub> </em>= mass of the sample.

However, adiabatic conditions are difficult to maintain. Fig. 2 is copied from the kit manual for the calorimeter and shows a typical temperature profile from this calorimeter. As can be seen in the data from 1:00 pm to 1:20 pm, the temperature of the empty calorimeter is rising slowly in the room. The calorimeter temperature rises rapidly after a sample at 99.5°C is added at 1:21 pm.  By 1:23 pm, however, the temperature rise has slowed. During this time, the calorimeter loses thermal energy to the surroundings, in spite of the insulation. That temperature loss is clear after 1:25 pm. The description following Fig. 1 describes the procedure to extrapolate values for <em>T</em><sub>0</sub> and <em>T</em><sub>2</sub> from a linear fit of temperature measurements before the sample was added and after heat transfer to the surroundings began to be a major factor respectively.  The purpose of the extrapolation method is to account for heat loss before, during and after the experiment.

<strong>Figure 1</strong> Schematic of the calorimeter, and adiabatic system.




As one can see from the data in Fig. 2, the calorimeter temperature begins to rise immediately after the sample is introduced. The rise is at first rapid (time point A to point B), then slower. Then the temperature starts to decrease (point A to point C), as the calorimeter temperature is observed to fall from 25.5 °C to 25.2 °C in 12 minutes. This represents a change of 0.025 °C per minute. We must employ a method to compensate for this unaccounted heat loss. This method is outlined below for the data shown in Figure 2 and employs the following steps:

<ol>

 <li>Determine the approximate temperature of the calorimeter before addition of the sample by fitting a line to the pre-sample temperature data from 1:10pm to 1:20pm.</li>

 <li>Use the line to determine the temperature for the time the sample was added and its uncertainty, in this case 1:21 pm (time of sample addition). Note the extrapolated temperature at T<sub>Low</sub>(1:21).</li>

 <li>Fit a second line from the maximum temperature reading (i.e. 1:27pm) to the last temperature reading at 1:50pm.</li>

 <li>Extrapolate this line back to the time when the sample was added (i.e. 1:21pm) and note the extrapolated temperature and its uncertainty, T<sub>Hi</sub>(1:21). In this case T<sub>Low</sub>(1:21) and T<sub>Hi</sub>(1:21) temperatures are 20.3 °C and 25.7 °C respectively. These are approximately correct.</li>

 <li>Next, determine the average of these two temperatures (23.0 °C); and from the graph determine the time associated with this temperature (1:22 pm approximately).</li>

 <li>Extrapolate the line from the later readings back to 1:22 pm, T<sub>Hi</sub>(1:22). T<sub>Low</sub>(1:21) represents the initial temperature of the calorimeter, <em>T</em><sub>0</sub>, and T<sub>Hi</sub>(1:22) represents the final temperature of the calorimeter and sample at equilibrium, <em>T</em><sub>2</sub>, with a compensation for heat loss to enable the adiabatic assumption to be applied and Eq. (1) to be appropriate. Also calculate the associated uncertainty with this value.</li>

</ol>




<strong>Figure 2.</strong>  Typical temperature profile from calorimeter