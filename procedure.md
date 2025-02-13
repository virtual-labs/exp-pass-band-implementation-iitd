<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body>
    <ul>
        <li>
            <strong>Input Parameters:</strong>
            <ul>
                <li><strong>Carrier Frequency:</strong> Use the input field to enter the desired carrier frequency.</li>
                <li><strong>Sampling Frequency:</strong> Specify the sampling frequency to be used in the simulation.</li>
                <li><strong>Number of Bits:</strong> Enter the number of bits for the message signal, which will be randomly generated binary bits.</li>
                <li><strong>Bit Rate in bps:</strong> Define the bit rate (bps) for the signal.</li>
            </ul>
        </li>
      <h3>Steps:</h3>
        <li>
            <strong>1. Generate the Message Signal:</strong> 
            Click the <em>“Generate Message”</em> button to create a random binary message signal based on the specified number of bits.
        </li>
        <li>
            <strong>2. Generate the Carrier Signal:</strong> 
            Click the <em>“Generate Carrier”</em> button to generate the carrier wave using the carrier frequency and sampling frequency provided.
        </li>
        <li>
            <strong>3. Perform Modulation and Demodulation:</strong> 
            Click the <em>“Simulate" and "Demodulate”</em> button to perform the modulation (ASK, FSK, or PSK) and demodulation process on the randomly generated message signal using the generated carrier.
        </li>
        <li>
            <strong>4. Plot BER vs. SNR:</strong> 
            Click the <em>“Generate BER vs. SNR”</em> button to plot the Bit Error Rate (BER) against the Signal-to-Noise Ratio (SNR), providing insights into the system’s performance under varying noise conditions.
        </li>
        <li>
            <strong>5. Examine Constellation Diagrams:</strong> 
            Click the <em>“Generate Constellation”</em> button to view the constellation diagrams for the modulated signals. This feature also allows you to observe the effect of noise on the constellation points.
        </li>
        <li>
            <strong>6. Observe Results:</strong> 
            Review the generated plots and diagrams to understand the behavior and performance of the modulation schemes. You can make adjustments to the input parameters and repeat the process to explore different scenarios.
        </li>
    </ul>
</body>
</html>
