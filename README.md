# kmeans-video
Short video explaining KMeans clustering visually.
This repository contains a short video I created to visually explain how **KMeans clustering** works.  
It shows how centroids start, move toward the mean of their assigned points, and stabilize over multiple iterations.

# About
- Great for students or anyone learning about clustering.
- Helps visualize how the algorithm reassigns points and updates centroids until convergence.

Feel free to use this video in your own:
- Notebooks and ML tutorials
- Presentations or slides
- Teaching material

  # Usage
- Download the `KMEANS.mp4` file from this repository.
- Embed or play it in your Jupyter notebooks, presentations, or share it with your study group.

Example to embed in a Jupyter Notebook:

```python
from IPython.display import HTML

HTML("""
<video width="640" controls>
  <source src="https://raw.githubusercontent.com/RituDSML/kmeans-video/main/KMEANS.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
""")
