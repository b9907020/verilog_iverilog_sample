<h1 id="iverilog_sample" > iverilog_sample:</h1>
<hr>
<ul>
  <li>Download iverilog exe file:
    <ul>
      <li><em><a href="http://bleyer.org/icarus/">http://bleyer.org/icarus/</a></em></li>
    </ul>
  </li>
  <li>Install
  </li>
  <li>Setup emvironment variable path
    <ul>
      <li>File -> This PC -> Right Click (for Windows user)</li>	    
      <li>Properties</li>
      <li>Advanced system seetings</li>
      <li>Environment Variable</li>
      <li>System variable -> path -> Edit</li>
      <li>New -> C:\iverilog\bin</li>
      <li>New -> C:\iverilog\gtkwave\bin</li>
      <li>OK</li>
    </ul>
  </li>
  <li>cmd window (for Windows user)
    <ul>
      <li>C:\Users\verilogsample>iverilog add.v test_bench.v -o sample.vvp</li>
      <li>(C:\Users\verilogsample>iverilog -o sample.vvp rtl\*)</li>
      <li>C:\Users\verilogsample>vvp sample.vvp</li>
      <li>(C:\Users\verilogsample>iverilog -o sample.vvp rtl\*)</li>
    </ul>
  </li>
  <li>Waveform
	  <p>
    <img src="https://raw.githubusercontent.com/KuiLiangLin/verilog_iverilog_sample/master/Waveform.GIF" height="100%" width="100%">
    </p>
  </li>
</ul>
