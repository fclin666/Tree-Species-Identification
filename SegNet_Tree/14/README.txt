1�B11�B8�B10�B7�B2�B4 �s���� ���X�� �V�m�C��
3�B5�B6�B9�B12�B13�B14

del *_3.jpg
del *_5.jpg
del *_6.jpg
del *_9.jpg
del *_12.jpg
del *_13.jpg
del *_14.jpg

python -m venv tensorflow_2.0_V1


conda info --envs

conda create --name tensorflow_2.0_V1 python=3.6

conda create --name tensorflow1 python=3.6

conda activate aaa
conda activate tensorflow1 

conda activate tensorflow_2.0_V1

============= ���� src label ��Ӹ�Ƨ� =============
  python right_mask.py

=================train=================
��l����: 
1.�ݦ� src label ��Ӹ�Ƨ�  
2.���� generate_val.py ���� val ��Ƨ�
  python generate_val.py

�ϥΤ覡:
  python train.py -m segnet.h5
  python train.py -m "segnet_7+1.h5"

================predict================
��l����: 
1.�ݦ� �w�V�m segnet.h5 
2.�ݦ� val ��Ƨ����t�h�Ӹ�Ƨ�

�ϥΤ覡:
  python predict.py

================val================
��l����:
1.�w���X�Ӫ�each_result

�ϥΤ覡:
  python calc_pixel_sort.py