=======
NNDC��
=======


������Դ
=========

NNDC������ENDF/B VII.1 293.6K�����Ӻ˽����

 - ���Ӻ˽���⣺ http://www.nndc.bnl.gov/endf/b7.1/aceFiles/ENDF-B-VII.1-neutron-293.6K.tar.gz

 - �Ȼ��⣺http://www.nndc.bnl.gov/endf/b7.1/aceFiles/ENDF-B-VII.1-tsl.tar.gz


ʹ�÷�ʽ
=========

  .. code-block:: sh

        git clone --branch=master https://github.com/thu-real/RMC_TestNucData.git testdatalib
        cp -r testdatalib/* $HOME/nucdata/
        rm -rf testdatalib
        python $HOME/nucdata/endfb7.1_nndc/update_xsdir.py
