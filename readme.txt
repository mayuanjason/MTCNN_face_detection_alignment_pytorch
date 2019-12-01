# STAGE 1
inds[2][434]                    tuple
tx1.shape (439,)                <class 'numpy.ndarray'>
score.shape (434,)              <class 'numpy.ndarray'>
offsets.shape (4, 434)          <class 'numpy.ndarray'>
bounding_boxes.shape (9, 434)   <class 'numpy.ndarray'>
boxes.shape (434, 9)            <class 'numpy.ndarray'>
            [n_boxes, 9]
			
[x1_origin, y1_origin, x2_origin, y2_origin, score, dx1, dy1, dx2, dy2]
...
n_boxes 个

bounding_boxes.shape (n, 5) 并且是方框
[x1_calibration, y1_calibration, x2_calibration, y2_calibration， score]


# STAGE 2                                       24    24
img_boxes: a float numpy array of shape [n, 3, size, size].

