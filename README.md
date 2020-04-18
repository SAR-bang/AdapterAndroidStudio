# AdapterAndroidStudio
Week6 College


singleAdapter extends RecyclerView.Adapter<view holder>

&& ---------------list model

oncreate ViewHolder
   ## create a view parent context =======-=+ item_layout(Recyclerciew ) not attached to  root 



onBind ViewHolder
get the data using the model class
based upon the position

eg,int img  = modelclasslist.get(position).getImage();



#1 view holder class extends view holder

** required args

setData()
