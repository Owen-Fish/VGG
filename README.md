# VGG
Store several original model of CNNS
# Inceptionv1
here are basic block of inceptionv1:https://cn.bing.com/images/search?view=detailV2&id=45AF2681E9F03A94D36DC58E0C215595A2C90C62&thid=OIP.LLq33roQ395gfpMRjjZUjQHaEq&mediaurl=https%3A%2F%2Fcdn-images-1.medium.com%2Fmax%2F1600%2F1*U_McJnp7Fnif-lw9iIC5Bw.png&exph=518&expw=823&q=inceptionv1&selectedindex=4&ajaxhist=0&vt=0&eim=1,2,6

here are scheme of inceptionv1:https://cn.bing.com/images/search?view=detailV2&id=8DA754805C8EAC0B4D81A1D9726C647362A93D8A&thid=OIP.ukSvzmeK1f2H9NiWp3IsrwHaCL&mediaurl=http%3A%2F%2Fjoelouismarino.github.io%2Fimages%2Fblog_images%2Fblog_googlenet_keras%2Fgooglenet_diagram.png&exph=584&expw=1984&q=inceptionv1&selectedindex=0&ajaxhist=0&vt=0&eim=1,2,6

here are paper about inceptionv1:https://arxiv.org/abs/1409.4842

# Inceptionv2
there are two different parts that between inceptionv1 and inceptionv2.
    1) Batch Normalization
    2) using two 3*3 kernel take place one 5*5 kernel
    because of using Batch Normalization dropout stage can be dropped
    In inceptionv1 there have one main output and two auxiliary output, I dropout one of these two auxiliary output. So
    in inceptionv2 there have one main output and one auxiliary output
