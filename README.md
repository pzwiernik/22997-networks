# Networks, Crowds and Markets - Fall 2025

<table>
<tr>
<td style="width:45%; vertical-align:top;">
  <img src="cover_image.png" alt="Course cover" width="100%">
</td>
<td style="width:55%; vertical-align:top; padding-left:15px;">
  This course offers an introduction to the mathematics of networks, their dynamics, and their applications in economics and the social sciences. We combine rigorous probabilistic models with real-world data and case studies, moving from the basics of Erdős–Rényi random graphs to power laws, small-world phenomena, clustering, and preferential attachment.
</td>
</tr>
</table>

***

### Announcements:
- The following [problem set](./seminars/Problem_set.pdf) contains exercises covering most of the course. We will use it for the seminars.
- **update:** The midterm is scheduled for Monday, November 3, during the lecture.
- I added the proof sketches for both theorems of Lecture 2. The slides have been updated. 
- The first lecture is on September 29, 3-4:30pm, in room 40.063. 

***

### Instructor:

| Prof |  [Piotr Zwiernik](https://pzwiernik.github.io/) |
| :--- | :--- |
| Email | piotr.zwiernik@upf.edu |
| Office hours | Tuesday 2-3pm (20.202) |


### Time & Location:


Lectures: Monday 3-4:30pm (40.063) and Tuesday 3-4:30pm (40.063).

Tutorials (group 1): 3-4:30pm (20.101)
Tutorials (group 2): 4:30-6pm (20.101)

There are six tutorial sessions, in weeks: 3,4,5,6,7,8. 

***

### Suggested Reading
The following books complement the material presented in the lecture.

* (EK) Easley, Kleinberg (2010). Networks, Crowds, and Markets: Reasoning About a Highly Connected World. Cambridge University Press. [Available online](https://www.cs.cornell.edu/home/kleinber/networks-book/networks-book.pdf)
* (B) Barabási (2016). Network Science. Cambridge University Press. [Available online](https://networksciencebook.com/)
* (N) Newman (2010). Networks: An Introduction. Oxford University Press.
* (MFD) Menczer, Fortunato, David (2020). A First Course in Network Science. Cambridge University Press. [Available online](https://cambridgeuniversitypress.github.io/FirstCourseNetworkScience/)
* (SK) Saoub (2017). A Tour Through Graph Theory. Springer.


***

## Lectures and timeline (tentative)


| Week | Topic  | Slides | Tutorials | Colabs | Lectures date  | Timeline |
| --- |  --- | --- | --- | --- | --- | --- | 
| 1 | Motivation and first examples. <br> Special graphs, degree.  | [slides1](./slides/lecture1.pdf)  <br> [slides2](./slides/lecture2.pdf)| - | [colab1](https://github.com/pzwiernik/22997-networks/blob/31f53e57e3c1bdad73fb6626f2a0ac5a1367d621/colabs/NetworkNotebook1.ipynb)| 29/30 Sept |  |
| 2 | Degree distribution, graph isomorphism, adjacency matrix. <br> Distance in graphs, diameter, connectivity, trees.  | [slides3](./slides/lecture3.pdf) <br> slides4 | -| [degree](https://github.com/pzwiernik/22997-networks/blob/31f53e57e3c1bdad73fb6626f2a0ac5a1367d621/colabs/Lecture3.ipyn)| | 6/7 Oct | report topics published|
| 3 | Erdös–Rényi model, degrees, threshold phenomena.<br> Clustering, other random graph models, preferential attachment.| slides5 <br> slides6| | | 13/14 Oct |   |
| 4 |  Small world, latent space random graphs.<br> Power laws and hubs.  | slides7 <br> slides8|  | | 20/21 Oct |  |
| 5 | Average path length, models with flexible degree distributions. <br> The Barabási-Albert Model, Centrality measures |slides9 <br> slides10 | | | 27/28 Oct | |  |
| 6 | midterm <br> Eigenvalue centrality, Pagerank algorithm.  |  <br> slides12| | | 3/4 Nov| midterm |
| 7 | Communities: definition and identification. Stochastic Block Model. <br> Social networks, forming mechanism. | slides13 <br> slides14|  | | 10/11 Nov | deadline reports <br> presentations 1|
| 8 | Matching markets <br> Spreading phenomena | slides15 <br> slides16| | | 17/18 Nov| presentations 2 |
| 9 |   | slides17 <br> slides18| - | | 24/25 Nov| |
| 10 | |slides19 <br> slides20 | - | | 1/2 Dec| |

***

## NetworkX guidelines

Although coding is not an essential part of this course, it is a very important complementary part. As the absolute minimum, you should try to run the code provided in class. 

We use Python and NetworkX. Useful documentation and examples can be found on the [GitHub of MFD book](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/tree/master).

I suggest to start like that:
- Create a [Google Colab](https://colab.research.google.com/) account (you should be able to do it using your UPF account).
- Take a look at [MFD:Appendix A](https://github.com/CambridgeUniversityPress/FirstCourseNetworkScience/blob/de9b42e3953ed90616940a801f64489067c1b888/tutorials/Appendix%20-%20Python%20Tutorial.ipynb). No need to read it completely. Use it as a reference.
- Start with the [first colab](https://colab.research.google.com/drive/16r0vZQRAynCS0hAHtJxrkX0MHR6gK8Zp?usp=sharing).
