Table 1
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Method</th>
      <th>MMLU</th>
      <th>IFEval</th>
      <th>HumanEval</th>
      <th>MBPP</th>
      <th>UGMathBench</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Qwen2.5-1.5B-Math</td>
      <td>base</td>
      <td>22.91</td>
      <td>44.62</td>
      <td>52.09</td>
      <td>50.38</td>
      <td>13.96</td>
    </tr>
    <tr>
      <td>+VFPO</td>
      <td><strong>23.52</strong></td>
      <td><strong>48.82</strong></td>
      <td><strong>57.37</strong></td>
      <td><strong>55.24</strong></td>
      <td><strong>18.24</strong></td>
    </tr>
    <tr>
      <td rowspan="2">Qwen2.5-3B</td>
      <td>base</td>
      <td>22.95</td>
      <td>58.2</td>
      <td>74.4</td>
      <td>72.7</td>
      <td>26.64</td>
    </tr>
    <tr>
      <td>+VFPO</td>
      <td><strong>23.64</strong></td>
      <td><strong>62.31</strong></td>
      <td><strong>77.46</strong></td>
      <td><strong>75.33</strong></td>
      <td><strong>29.55</strong></td>
    </tr>
    <tr>
      <td rowspan="2">Qwen2.5-7B</td>
      <td>base</td>
      <td>25.60</td>
      <td>71.20</td>
      <td>84.82</td>
      <td>79.25</td>
      <td>31.42</td>
    </tr>
    <tr>
      <td>+VFPO</td>
      <td><strong>26.84</strong></td>
      <td><strong>74.83</strong></td>
      <td><strong>88.69</strong></td>
      <td><strong>80.27</strong></td>
      <td><strong>34.60</strong></td>
    </tr>
  </tbody>
</table>




<figure>
  <embed src="clip_grad.pdf" width="100%" height="500px" type="application/pdf" />
  <figcaption style="text-align: center;">Figure 1</figcaption>
</figure>
