# Learning-ML

## labelImg Download
    - https://towardsdatascience.com/how-to-label-images-for-object-detection-step-by-step-7ee317f98583

    - *Possible Error*
        download labelImg -> pip3 install lebelImg -> python labelImg.py -> bị lỗi "ModuleNotFoundError: No module named 'libs.resources'"-> pyrcc5 -o libs/resources.py resources.qrc -> python labelImg.py -> ok :D :D
        source -->https://github.com/heartexlabs/labelImg/issues/510

## To create automate requirements.txt
    - pip freeze > requirements.txt
        list all the files installed by pip command
    - pipreqs --encoding utf-8 "./" --force
        didn't work for me
    - session_info.show(html=False) #in code for ipynb file
        list the file in one file than copy/paste in requirements.txt