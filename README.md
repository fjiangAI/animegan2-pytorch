It's an out-of-the-box animegan2 that is modified from the [original version](https://github.com/bryandlee/animegan2-pytorch).

So how to run it?


1. pip install -r requirements.txt
2. put the origin pictures into the samples/inputs (please notice the max shape of the picture is 600\*800 in 24G GPU.)
3. python3 test.py --checkpoint ./weights/face_paint_512_v2.pt
4. get the converted pictures from the samples/results

More details can be seen the [blog](https://fjiang.blog.csdn.net/article/details/121455898).
