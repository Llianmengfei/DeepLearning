# DeepLearning
深度学习库

import tensorflow as tf

hello = tf.constant('hello tensorflow')

with tf.Session() as sess:
  print(sess.run(hello))
