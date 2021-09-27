## Tim 1

1. Belajar [Tensorflow](https://www.tensorflow.org/)
2. Belajar [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) (Free GPU)
3. Belajar tentang *time-series prediction* dan *forecasting* dengan Tensorflow
4. Cari paper/jurnal terbaru terkait **System Identification** dengan **Machine Learning**/**Deep Learning**/**Neural Networks**

**Sources**: 
- [DeepLearning.AI TensorFlow Developer Professional Certificate](https://www.coursera.org/professional-certificates/tensorflow-in-practice)
  - [Course 1](https://www.coursera.org/learn/introduction-tensorflow?specialization=tensorflow-in-practice)
  - [Course 4](https://www.coursera.org/learn/tensorflow-sequences-time-series-and-prediction?specialization=tensorflow-in-practice)
- [Time series forecasting - Google](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/structured_data/time_series.ipynb)

**Notes**:
- Sambil nyari yang 4., sambil ngecek apakah udah ada orang yang melakukan riset dengan approach yang sama dengan kita apa belum.

## Tim 2:

1. Pelajari dataset [1](https://github.com/fadamsyah/Particle-Based-Optimization-for-Longitudinal-Control/tree/main/S2_System_Identification/data/training_data) dan [2](https://github.com/fadamsyah/Particle-Based-Optimization-for-Longitudinal-Control/tree/main/S2_System_Identification/data/test_data)
2. Pelajari dataset [KITTI](http://www.cvlibs.net/datasets/kitti/)
3. Pelajari dataset [NCLT](http://robots.engin.umich.edu/nclt/)
4. Siapin dataset **1**, **2**, dan **3** supaya nanti bisa dipake untuk Tim 1 (*format* nya maksudnya disamain)
5. Pelajari FPA untuk system identification: [summary: section 2](https://unijourn.com/article/5f7eadeb7c994c603b93ad6d/5ae99ad07348a8567766abe2/4.html), [Implementation](https://github.com/fadamsyah/Particle-Based-Optimization-for-Longitudinal-Control/tree/main/S2_System_Identification/A4_MFPA)
6. Pelajari **Vehicle longitudinal model** yang klasik (yang diturunin secara **matematis** dan **fisis**). Kalau bisa, cari yang ada **simulasinya** ya

**Notes**:
- *Input* yang dibutuhkan model nantinya adalah yang berhubungan dengan aktuasi mobil, seperti *throttle*, *brake*, dan *steering angle* (atau yang sejenisnya)
- Data *steering angle* (atau yang sejenisnya) ga harus ada
- *Output* utama yang kita perlukan adalah **kecepatan** atau **kelajuan**