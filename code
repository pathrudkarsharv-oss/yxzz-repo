class DNASample:
  def __init__(self,name,sequence_length):
    self.name= name
    self.sequence_length=sequence_length

Sample_1= DNASample("Sample_Alpha", 1500)
Sample_2= DNASample("Sample_Beta" ,0)
Sample_3= DNASample("Sample_Gamma", 2200)

lab_rack = [Sample_1 , Sample_2 , Sample_3]
print("---STRATING BIO-PIPELINE RUN---")
for sample in lab_rack :
 try:
  if sample.sequence_length==0:
     trigger_fuse = 10/0
     print("Success", sample.name ,"is healthy and processing.")
 except:
  print("Alert! Failed sample:", sample.name , "has sequence length of 0.")
  print("---PIPELINE RUN COMPLETE---")
