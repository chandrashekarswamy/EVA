# convolutional-neural-network

## Assignment 1B

* Kernels 

    Kernels are feature extractor or filters, we use 3*3 matrix to extract the necessary feature from the input file.
    OR
    Kernel is a key functions used to extract necessary information from the frame/picture so that we can take certain decision to 
    identify the edges & Gradients/texture/patterns/parts of object/object.
    
* Channels

    Channels are set of similar features OR Fundamental building blocks of images.
    
* 3*3

    We need to use 3\*3 because it uses less number of values get the results compared to other kernels
    example : 
          5\*5 to 1\*1 if we use kernel of 5\*5 we need only one kernel so have to work on 25 values.
          5\*5 to 1\*1 if we use kernel of 3\*3 we need two 3\*3 kernels so 9+9 = 18 values.
          
    As the trend started growing for using the 3\*3 kernels NVIDEA prepared optimised architecture so that 3*3 kernal perfrom 
    faster compared to other kernels so its always better to use 3\*3 kernels.(yet to read about this )

#### INPUT  | Convolution Layer | OUTPUT

199\*199	|  Kernel of 3\*3 |	197\*197

197\*197	|  Kernel of 3\*3 |	195\*195

195\*195	|  Kernel of 3\*3 |	193\*193

193\*193	|  Kernel of 3\*3 |	191\*191

191\*191	|  Kernel of 3\*3 |	189\*189

189\*189	|  Kernel of 3\*3 |	187\*187

187\*187	|  Kernel of 3\*3 |	185\*185

185\*185	|  Kernel of 3\*3 |	183\*183

183\*183	|  Kernel of 3\*3 |	181\*181

181\*181	|  Kernel of 3\*3 |	179\*179

179\*179	|  Kernel of 3\*3 |	177\*177

177\*177	|  Kernel of 3\*3 |	175\*175

175\*175	|  Kernel of 3\*3 |	173\*173

173\*173	|  Kernel of 3\*3 |	171\*171

171\*171	|  Kernel of 3\*3 |	169\*169

169\*169	|  Kernel of 3\*3 |	167\*167

167\*167	|  Kernel of 3\*3 |	165\*165

165\*165	|  Kernel of 3\*3 |	163\*163

163\*163	|  Kernel of 3\*3 |	161\*161

161\*161	|  Kernel of 3\*3 |	159\*159

159\*159	|  Kernel of 3\*3 |	157\*157

157\*157	|  Kernel of 3\*3 |	155\*155

155\*155	|  Kernel of 3\*3 |	153\*153

153\*153	|  Kernel of 3\*3 |	151\*151

151\*151	|  Kernel of 3\*3 |	149\*149

149\*149	|  Kernel of 3\*3 |	147\*147

147\*147	|  Kernel of 3\*3 |	145\*145

145\*145	|  Kernel of 3\*3 |	143\*143

143\*143	|  Kernel of 3\*3 |	141\*141

141\*141	|  Kernel of 3\*3 |	139\*139

139\*139	|  Kernel of 3\*3 |	137\*137

137\*137	|  Kernel of 3\*3 |	135\*135

135\*135	|  Kernel of 3\*3 |	133\*133

133\*133	|  Kernel of 3\*3 |	131\*131

131\*131	|  Kernel of 3\*3 |	129\*129

129\*129	|  Kernel of 3\*3 |	127\*127

127\*127	|  Kernel of 3\*3 |	125\*125

125\*125	|  Kernel of 3\*3 |	123\*123

123\*123	|  Kernel of 3\*3 |	121\*121

121\*121	|  Kernel of 3\*3 |	119\*119

119\*119	|  Kernel of 3\*3 |	117\*117

117\*117	|  Kernel of 3\*3 |	115\*115

115\*115	|  Kernel of 3\*3 |	113\*113

113\*113	|  Kernel of 3\*3 |	111\*111

111\*111	|  Kernel of 3\*3 |	109\*109

109\*109	|  Kernel of 3\*3 |	107\*107

107\*107	|  Kernel of 3\*3 |	105\*105

105\*105	|  Kernel of 3\*3 |	103\*103

103\*103	|  Kernel of 3\*3 |	101\*101

101\*101	|  Kernel of 3\*3 |	99\*99

99\*99	|  Kernel of 3\*3 |	97\*97

97\*97	|  Kernel of 3\*3 |	95\*95

95\*95	|  Kernel of 3\*3 |	93\*93

93\*93	|  Kernel of 3\*3 |	91\*91

91\*91	|  Kernel of 3\*3 |	89\*89

89\*89	|  Kernel of 3\*3 |	87\*87

87\*87	|  Kernel of 3\*3 |	85\*85

85\*85	|  Kernel of 3\*3 |	83\*83

83\*83	|  Kernel of 3\*3 |	81\*81

81\*81	|  Kernel of 3\*3 |	79\*79

79\*79	|  Kernel of 3\*3 |	77\*77

77\*77	|  Kernel of 3\*3 |	75\*75

75\*75	|  Kernel of 3\*3 |	73\*73

73\*73	|  Kernel of 3\*3 |	71\*71

71\*71	|  Kernel of 3\*3 |	69\*69

69\*69	|  Kernel of 3\*3 |	67\*67

67\*67	|  Kernel of 3\*3 |	65\*65

65\*65	|  Kernel of 3\*3 |	63\*63

63\*63	|  Kernel of 3\*3 |	61\*61

61\*61	|  Kernel of 3\*3 |	59\*59

59\*59	|  Kernel of 3\*3 |	57\*57

57\*57	|  Kernel of 3\*3 |	55\*55

55\*55	|  Kernel of 3\*3 |	53\*53

53\*53	|  Kernel of 3\*3 |	51\*51

51\*51	|  Kernel of 3\*3 |	49\*49

49\*49	|  Kernel of 3\*3 |	47\*47

47\*47	|  Kernel of 3\*3 |	45\*45

45\*45	|  Kernel of 3\*3 |	43\*43

43\*43	|  Kernel of 3\*3 |	41\*41

41\*41	|  Kernel of 3\*3 |	39\*39

39\*39	|  Kernel of 3\*3 |	37\*37

37\*37	|  Kernel of 3\*3 |	35\*35

35\*35	|  Kernel of 3\*3 |	33\*33

33\*33	|  Kernel of 3\*3 |	31\*31

31\*31	|  Kernel of 3\*3 |	29\*29

29\*29	|  Kernel of 3\*3 |	27\*27

27\*27	|  Kernel of 3\*3 |	25\*25

25\*25	|  Kernel of 3\*3 |	23\*23

23\*23	|  Kernel of 3\*3 |	21\*21

21\*21	|  Kernel of 3\*3 |	19\*19

19\*19	|  Kernel of 3\*3 |	17\*17

17\*17	|  Kernel of 3\*3 |	15\*15

15\*15	|  Kernel of 3\*3 |	13\*13

13\*13	|  Kernel of 3\*3 |	11\*11

11\*11	|  Kernel of 3\*3 |	9\*9

9\*9	|  Kernel of 3\*3 |	7\*7

7\*7	|  Kernel of 3\*3 |	5\*5

5\*5	|  Kernel of 3\*3 |	3\*3

3\*3	|  Kernel of 3\*3 |	1\*1
