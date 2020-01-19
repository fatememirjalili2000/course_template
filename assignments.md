---
layout: page
title: Assignments
permalink: /assignments/
---

<ul id="archive">
{% for asg in site.assignments reversed %}
      <li class="archiveposturl" style="background: transparent">
        <span><a href="{{ asg.url | prepend: site.baseurl}}">{{ asg.title }}</a></span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
<a title="Download problems (pdf)" href="{{ asg.pdf | prepend: site.baseurl }}"><i class="fas fa-file-pdf"></i></a> 
{% if asg.attachment %}
&nbsp; <a title="Download attachments (zip)" href="{{ asg.attachment | prepend: site.baseurl }}"><i class="fas fa-file-archive"></i></a>
{% endif %}
</strong> 
      </li>
{% endfor %}
</ul>

<strong>You can download the assignments here (in PDF format).</strong>


<strong>Assignment 1</strong>
<a href="https://quera.ir/course/assignments/10484/get_pdf_file">PDF</a>
<br>
<strong>Assignment 2</strong>
<a href= "https://quera.ir/course/assignments/10574/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 3</strong>
<a href="https://quera.ir/course/assignments/10751/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 4</strong>
<a href="https://quera.ir/course/assignments/10894/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 5</strong>
<a href="https://quera.ir/course/assignments/11189/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 6</strong>
<a href="https://quera.ir/course/assignments/11360/get_pdf_file ">PDF</a>
<br> 
<strong>Assignment 7</strong>
<a href="https://quera.ir/course/assignments/11611/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 8</strong>
<a href="https://quera.ir/course/assignments/12045/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 9 </strong>
<a href="https://quera.ir/course/assignments/12329/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 10</strong>
<a href="https://quera.ir/course/assignments/12551/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 11</strong>
<a href="https://quera.ir/course/assignments/12816/get_pdf_file">PDF</a>
<br> 
<strong>Simulation Assignment</strong>
<a href="https://quera.ir/course/assignments/12553/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 12</strong>
<a href="https://quera.ir/course/assignments/13097/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 13</strong>
<a href="https://quera.ir/course/assignments/13251/get_pdf_file">PDF</a>
<br> 
<strong>Assignment 14</strong>
<a href="https://quera.ir/course/assignments/13457/get_pdf_file">PDF</a>

