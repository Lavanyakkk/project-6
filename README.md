def rename():
    i=1
    path="C:\\Users\\lavanya\\PycharmProjects\\pythonProject2\\images"
    for filename in os.listdir(path):
        picturenames=f"pic(i).jpg"
        source=path+filename
        destination=path+picturenames
        os.rename(src,destination)
        i=i+1
if _name_=="_main_":
    rename()
