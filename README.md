# detecting-objects-via-frequency-signatures
The project uses a spatiotemporal seismometer to collect signals at regular intervals, and analyzes them in the frequency domain using fast Fourier transform to detect object location. Applying filters to reduce noise and enhance signals helps to locate the object more accurately, and results are presented through figures.
<h3>Project report CP1.pdf includes all the results and plots</h3>

<!DOCTYPE html>
<html>
  <body>
    <h1>Le Kraken de Seattle</h1>
    <p>There’s a Kraken under the ice in Climate Pledge Arena. The players know that if the Kraken’s position coincides with that of the opponent, they can land a hard check. The movement of the Kraken causes vibrations to be carried up through the ice that the players can’t feel, but can be measured by a spatio-temporal seismometer at 1 minute and 15 second intervals, which is given in Kraken.mat and Kraken.csv.</p>
    <p>The team (and you) should do the following:</p>
    <ol>
      <li>Through averaging of the spectrum, determine the frequency that the signals are centered about.</li>
      <li>Filter the data in order to determine the path of the Kraken (plot the path as a 3-D curve).</li>
      <li>What points on the ice would be optimal for a defenceman to be to make a hard check (i.e., take that 3-D curve and plot the (x, y) points).</li>
    </ol>
    <p>Please also write a short report in the style of a scientific article. You will be given templates for the code (to match it with the rubric in the autograder) and the report to help you write it.</p>
    <p>You may use the code CP1_sample.m to help you start analyzing the data. In the code we can see what happens when we threshold the data; i.e., we consider frequencies only above a certain strength. See what happens if you use a threshold of 0.3, 0.5, 0.7, and 0.9. Out of those, which gives you the most amount of data with the least (or an acceptable) amount of noise?</p>
  </body>
</html>
