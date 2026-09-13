<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js" async></script>
</head>
<body>

<p>
Digital modulation schemes are techniques used to encode information onto a high-frequency carrier by varying its amplitude, frequency, or phase according to discrete signal levels or symbols. Here’s an overview of three common digital modulation schemes: 
<b>Amplitude Shift Keying (ASK)</b>, <b>Frequency Shift Keying (FSK)</b>, and <b>Phase Shift Keying (PSK)</b>.
</p>

<p class="mb-4">
<b>Passband Amplitude Shift Keying (ASK)</b> modulates the amplitude of a carrier signal according to the input binary sequence. In binary ASK (BASK), a binary '1' is transmitted as a carrier with amplitude \(A_c\), while a binary '0' is transmitted by reducing the carrier amplitude to zero. This ON-OFF characteristic makes ASK simple to implement, though it is sensitive to noise and amplitude variations.
</p>

<p class="mb-4">
<b>Passband Frequency Shift Keying (FSK)</b> represents binary values using two distinct carrier frequencies. For instance, binary '1' is transmitted using a higher frequency \(f_1\) (mark), and binary '0' uses a lower frequency \(f_2\) (space). The frequency changes are constant-amplitude, which makes FSK more robust than ASK in the presence of amplitude noise and suitable for RF or band-limited channels.
</p>

<p class="mb-4">
<b>Passband Phase Shift Keying (PSK)</b> encodes information by varying the phase of the carrier signal. In binary PSK (BPSK), binary '1' is represented by a 180° phase shift relative to the previous symbol, while binary '0' retains the same phase. PSK offers high power efficiency and better noise immunity than ASK and FSK, at the cost of more complex receiver design.
</p>

<p class="mb-4">
Each modulation scheme is selected based on system requirements such as bandwidth efficiency, power efficiency, noise resilience, and implementation complexity. Passband modulation allows these digital signals to be transmitted over RF, optical, or other band-limited channels.
</p>

<br><br>

<h3>Passband Digital Modulation Techniques</h3>

<ol class="mb-4 pl-4 list-decimal text-[#007bff] font-normal text-[19.2px]" style="font-family: Raleway, sans-serif">
  <li>
    <a href="./ASK.html" class="hover:text-[#3e6389] hover:underline">
      Passband Amplitude Shift Keying (ASK)
    </a>
  </li>
  <li>
    <a href="./FSK.html" class="hover:text-[#3e6389] hover:underline">
      Passband Frequency Shift Keying (FSK)
    </a>
  </li>
  <li>
    <a href="./PSK.html" class="hover:text-[#3e6389] hover:underline">
      Passband Phase Shift Keying (PSK)
    </a>
  </li>
</ol>

</body>
</html>
