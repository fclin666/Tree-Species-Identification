train ==> 
python CNNtrainAndTest.py -type 0 -folder \14\Original  -network resnet -weight Resnet_Original_14.hdf5
python CNNtrainAndTest.py -type 0 -folder \14\Feature -network resnet -weight Resnet_Feature_14.hdf5
python CNNtrainAndTest.py -type 0 -folder \14\PCA -network resnet -weight Resnet_PCA_14.hdf5
python CNNtrainAndTest.py -type 0 -folder \7\Original  -network resnet -weight Resnet_Original_7.hdf5
python CNNtrainAndTest.py -type 0 -folder \7\Feature -network resnet -weight Resnet_Feature_7.hdf5
python CNNtrainAndTest.py -type 0 -folder \7\PCA -network resnet -weight Resnet_PCA_7.hdf5

test ==> 
python CNNtrainAndTest.py -type 1 -folder \14\Original  -network resnet -weight Resnet_Original_14.hdf5
python CNNtrainAndTest.py -type 1 -folder \14\Feature -network resnet -weight Resnet_Feature_14.hdf5
python CNNtrainAndTest.py -type 1 -folder \14\PCA -network resnet -weight Resnet_PCA_14.hdf5
python CNNtrainAndTest.py -type 1 -folder \7\Original  -network resnet -weight Resnet_Original_7.hdf5
python CNNtrainAndTest.py -type 1 -folder \7\Feature -network resnet -weight Resnet_Feature_7.hdf5
python CNNtrainAndTest.py -type 1 -folder \7\PCA -network resnet -weight Resnet_PCA_7.hdf5

getLayers.py : ����C�h�Ϥ����S�x��

python getLayers.py -image XXX.jpg -network resnet

-image: ���w��J�Ϥ�
-network: ���w�����[�c resnet vgg segnet

CNNtrainAndTest.py : �V�m�M���հV�m���G

train ==> 
python CNNtrainAndTest.py -type 0 -folder Original -network resnet -weight Resnet_Original_14.hdf5

test ==> 
python CNNtrainAndTest.py -type 1 -folder Original -network resnet -weight Resnet_Original_14.hdf5

python CNNtrainAndTest.py -type X -folder XXX -network XXX -weight XXX.hdf5

-type: �V�m��0 ���լ�1
-folder: ���w�V�m��Ƨ�(�|�ۤv�s����Ƨ�����"train"�M"vali"�A �p�G�O���իh�O"test")

-network: ���w�V�m����(vgg or resnet)

-weight: ���J���ո�Ƨ��A�p�G�O���դ��i����