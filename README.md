# Pneumonia_Detection
Pneumonia Detection from Chest X-Ray Images using Transfer Learning

Domain             : Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Inception


Description

1. Detected Pneumonia from Chest X-Ray images using Custom Deep Convololutional Neural Network and by retraining pretrained model “InceptionV3” 
2. For retraining removed output layers, freezed first few layers and fine-tuned model for two new label classes (Pneumonia and Normal).



Dataset

Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia


Dataset Details
Dataset Name            : Chest X-Ray Images (Pneumonia)
Number of Class         : 2


Model Parameters
Machine Learning Library: Keras
Base Model              : InceptionV3 && Custom Deep Convolutional Neural Network
Optimizers              : Adam
Loss Function           : categorical_crossentropy

For Custom Deep Convolutional Neural Network : 
Training Parameters
Batch Size              : 32
Number of Epochs        : 50
Training Time           : 7 Hours



Training Model:
0 input_1
1 conv2d_1
2 batch_normalization_1
3 activation_1
4 conv2d_2
5 batch_normalization_2
6 activation_2
7 conv2d_3
8 batch_normalization_3
9 activation_3
10 max_pooling2d_1
11 conv2d_4
12 batch_normalization_4
13 activation_4
14 conv2d_5
15 batch_normalization_5
16 activation_5
17 max_pooling2d_2
18 conv2d_9
19 batch_normalization_9
20 activation_9
21 conv2d_7
22 conv2d_10
23 batch_normalization_7
24 batch_normalization_10
25 activation_7
26 activation_10
27 average_pooling2d_1
28 conv2d_6
29 conv2d_8
30 conv2d_11
31 conv2d_12
32 batch_normalization_6
33 batch_normalization_8
34 batch_normalization_11
35 batch_normalization_12
36 activation_6
37 activation_8
38 activation_11
39 activation_12
40 mixed0
41 conv2d_16
42 batch_normalization_16
43 activation_16
44 conv2d_14
45 conv2d_17
46 batch_normalization_14
47 batch_normalization_17
48 activation_14
49 activation_17
50 average_pooling2d_2
51 conv2d_13
52 conv2d_15
53 conv2d_18
54 conv2d_19
55 batch_normalization_13
56 batch_normalization_15
57 batch_normalization_18
58 batch_normalization_19
59 activation_13
60 activation_15
61 activation_18
62 activation_19
63 mixed1
64 conv2d_23
65 batch_normalization_23
66 activation_23
67 conv2d_21
68 conv2d_24
69 batch_normalization_21
70 batch_normalization_24
71 activation_21
72 activation_24
73 average_pooling2d_3
74 conv2d_20
75 conv2d_22
76 conv2d_25
77 conv2d_26
78 batch_normalization_20
79 batch_normalization_22
80 batch_normalization_25
81 batch_normalization_26
82 activation_20
83 activation_22
84 activation_25
85 activation_26
86 mixed2
87 conv2d_28
88 batch_normalization_28
89 activation_28
90 conv2d_29
91 batch_normalization_29
92 activation_29
93 conv2d_27
94 conv2d_30
95 batch_normalization_27
96 batch_normalization_30
97 activation_27
98 activation_30
99 max_pooling2d_3
100 mixed3
101 conv2d_35
102 batch_normalization_35
103 activation_35
104 conv2d_36
105 batch_normalization_36
106 activation_36
107 conv2d_32
108 conv2d_37
109 batch_normalization_32
110 batch_normalization_37
111 activation_32
112 activation_37
113 conv2d_33
114 conv2d_38
115 batch_normalization_33
116 batch_normalization_38
117 activation_33
118 activation_38
119 average_pooling2d_4
120 conv2d_31
121 conv2d_34
122 conv2d_39
123 conv2d_40
124 batch_normalization_31
125 batch_normalization_34
126 batch_normalization_39
127 batch_normalization_40
128 activation_31
129 activation_34
130 activation_39
131 activation_40
132 mixed4
133 conv2d_45
134 batch_normalization_45
135 activation_45
136 conv2d_46
137 batch_normalization_46
138 activation_46
139 conv2d_42
140 conv2d_47
141 batch_normalization_42
142 batch_normalization_47
143 activation_42
144 activation_47
145 conv2d_43
146 conv2d_48
147 batch_normalization_43
148 batch_normalization_48
149 activation_43
150 activation_48
151 average_pooling2d_5
152 conv2d_41
153 conv2d_44
154 conv2d_49
155 conv2d_50
156 batch_normalization_41
157 batch_normalization_44
158 batch_normalization_49
159 batch_normalization_50
160 activation_41
161 activation_44
162 activation_49
163 activation_50
164 mixed5
165 conv2d_55
166 batch_normalization_55
167 activation_55
168 conv2d_56
169 batch_normalization_56
170 activation_56
171 conv2d_52
172 conv2d_57
173 batch_normalization_52
174 batch_normalization_57
175 activation_52
176 activation_57
177 conv2d_53
178 conv2d_58
179 batch_normalization_53
180 batch_normalization_58
181 activation_53
182 activation_58
183 average_pooling2d_6
184 conv2d_51
185 conv2d_54
186 conv2d_59
187 conv2d_60
188 batch_normalization_51
189 batch_normalization_54
190 batch_normalization_59
191 batch_normalization_60
192 activation_51
193 activation_54
194 activation_59
195 activation_60
196 mixed6
197 conv2d_65
198 batch_normalization_65
199 activation_65
200 conv2d_66
201 batch_normalization_66
202 activation_66
203 conv2d_62
204 conv2d_67
205 batch_normalization_62
206 batch_normalization_67
207 activation_62
208 activation_67
209 conv2d_63
210 conv2d_68
211 batch_normalization_63
212 batch_normalization_68
213 activation_63
214 activation_68
215 average_pooling2d_7
216 conv2d_61
217 conv2d_64
218 conv2d_69
219 conv2d_70
220 batch_normalization_61
221 batch_normalization_64
222 batch_normalization_69
223 batch_normalization_70
224 activation_61
225 activation_64
226 activation_69
227 activation_70
228 mixed7
229 conv2d_73
230 batch_normalization_73
231 activation_73
232 conv2d_74
233 batch_normalization_74
234 activation_74
235 conv2d_71
236 conv2d_75
237 batch_normalization_71
238 batch_normalization_75
239 activation_71
240 activation_75
241 conv2d_72
242 conv2d_76
243 batch_normalization_72
244 batch_normalization_76
245 activation_72
246 activation_76
247 max_pooling2d_4
248 mixed8
249 conv2d_81
250 batch_normalization_81
251 activation_81
252 conv2d_78
253 conv2d_82
254 batch_normalization_78
255 batch_normalization_82
256 activation_78
257 activation_82
258 conv2d_79
259 conv2d_80
260 conv2d_83
261 conv2d_84
262 average_pooling2d_8
263 conv2d_77
264 batch_normalization_79
265 batch_normalization_80
266 batch_normalization_83
267 batch_normalization_84
268 conv2d_85
269 batch_normalization_77
270 activation_79
271 activation_80
272 activation_83
273 activation_84
274 batch_normalization_85
275 activation_77
276 mixed9_0
277 concatenate_1
278 activation_85
279 mixed9
280 conv2d_90
281 batch_normalization_90
282 activation_90
283 conv2d_87
284 conv2d_91
285 batch_normalization_87
286 batch_normalization_91
287 activation_87
288 activation_91
289 conv2d_88
290 conv2d_89
291 conv2d_92
292 conv2d_93
293 average_pooling2d_9
294 conv2d_86
295 batch_normalization_88
296 batch_normalization_89
297 batch_normalization_92
298 batch_normalization_93
299 conv2d_94
300 batch_normalization_86
301 activation_88
302 activation_89
303 activation_92
304 activation_93
305 batch_normalization_94
306 activation_86
307 mixed9_1
308 concatenate_2
309 activation_94
310 mixed10
WARNING:tensorflow:From /home/kapil.rajput/PycharmProjects/Analytix/venv/lib/python3.6/site-packages/keras/callbacks/tensorboard_v1.py:200: The name tf.summary.merge_all is deprecated. Please use tf.compat.v1.summary.merge_all instead.

WARNING:tensorflow:From /home/kapil.rajput/PycharmProjects/Analytix/venv/lib/python3.6/site-packages/keras/callbacks/tensorboard_v1.py:203: The name tf.summary.FileWriter is deprecated. Please use tf.compat.v1.summary.FileWriter instead.

WARNING:tensorflow:From /home/kapil.rajput/PycharmProjects/Analytix/venv/lib/python3.6/site-packages/keras/backend/tensorflow_backend.py:422: The name tf.global_variables is deprecated. Please use tf.compat.v1.global_variables instead.

Epoch 1/1

  1/163 [..............................] - ETA: 58:08 - loss: 0.5346 - accuracy: 0.7812
  2/163 [..............................] - ETA: 44:05 - loss: 1.2034 - accuracy: 0.7812
  3/163 [..............................] - ETA: 38:46 - loss: 1.0600 - accuracy: 0.7708
  4/163 [..............................] - ETA: 36:45 - loss: 0.8608 - accuracy: 0.7969
  5/163 [..............................] - ETA: 34:57 - loss: 0.8745 - accuracy: 0.7437
  6/163 [>.............................] - ETA: 33:09 - loss: 0.7569 - accuracy: 0.7760
  7/163 [>.............................] - ETA: 31:42 - loss: 0.6659 - accuracy: 0.8036
  8/163 [>.............................] - ETA: 30:10 - loss: 0.6819 - accuracy: 0.8047
  9/163 [>.............................] - ETA: 28:44 - loss: 0.6207 - accuracy: 0.8194
 10/163 [>.............................] - ETA: 27:50 - loss: 0.5683 - accuracy: 0.8344
 11/163 [=>............................] - ETA: 27:14 - loss: 0.5464 - accuracy: 0.8409
 12/163 [=>............................] - ETA: 26:39 - loss: 0.5370 - accuracy: 0.8438
 13/163 [=>............................] - ETA: 26:13 - loss: 0.5060 - accuracy: 0.8510
 14/163 [=>............................] - ETA: 25:54 - loss: 0.4825 - accuracy: 0.8549
 15/163 [=>............................] - ETA: 25:24 - loss: 0.4630 - accuracy: 0.8583
 16/163 [=>............................] - ETA: 25:00 - loss: 0.4522 - accuracy: 0.8594
 17/163 [==>...........................] - ETA: 24:39 - loss: 0.4493 - accuracy: 0.8566
 18/163 [==>...........................] - ETA: 24:07 - loss: 0.4327 - accuracy: 0.8594
 19/163 [==>...........................] - ETA: 23:45 - loss: 0.4191 - accuracy: 0.8635
 20/163 [==>...........................] - ETA: 23:33 - loss: 0.4023 - accuracy: 0.8687
 21/163 [==>...........................] - ETA: 23:24 - loss: 0.3884 - accuracy: 0.8735
 22/163 [===>..........................] - ETA: 23:07 - loss: 0.3756 - accuracy: 0.8764
 23/163 [===>..........................] - ETA: 22:48 - loss: 0.3818 - accuracy: 0.8764
 24/163 [===>..........................] - ETA: 22:25 - loss: 0.3724 - accuracy: 0.8789
 25/163 [===>..........................] - ETA: 22:09 - loss: 0.3728 - accuracy: 0.8788
 26/163 [===>..........................] - ETA: 22:01 - loss: 0.3691 - accuracy: 0.8786
 27/163 [===>..........................] - ETA: 21:43 - loss: 0.3640 - accuracy: 0.8808
 28/163 [====>.........................] - ETA: 21:28 - loss: 0.3589 - accuracy: 0.8828
 29/163 [====>.........................] - ETA: 21:19 - loss: 0.3502 - accuracy: 0.8858
 30/163 [====>.........................] - ETA: 21:12 - loss: 0.3461 - accuracy: 0.8875
 31/163 [====>.........................] - ETA: 20:51 - loss: 0.3410 - accuracy: 0.8871
 32/163 [====>.........................] - ETA: 20:36 - loss: 0.3373 - accuracy: 0.8877
 33/163 [=====>........................] - ETA: 20:16 - loss: 0.3302 - accuracy: 0.8892
 34/163 [=====>........................] - ETA: 20:00 - loss: 0.3242 - accuracy: 0.8915
 35/163 [=====>........................] - ETA: 19:55 - loss: 0.3183 - accuracy: 0.8938
 36/163 [=====>........................] - ETA: 19:48 - loss: 0.3175 - accuracy: 0.8958
 37/163 [=====>........................] - ETA: 19:36 - loss: 0.3178 - accuracy: 0.8953
 38/163 [=====>........................] - ETA: 19:28 - loss: 0.3136 - accuracy: 0.8964
 39/163 [======>.......................] - ETA: 19:15 - loss: 0.3127 - accuracy: 0.8974
 40/163 [======>.......................] - ETA: 18:59 - loss: 0.3060 - accuracy: 0.9000
 41/163 [======>.......................] - ETA: 18:45 - loss: 0.3010 - accuracy: 0.9017
 42/163 [======>.......................] - ETA: 18:29 - loss: 0.2998 - accuracy: 0.9003
 43/163 [======>.......................] - ETA: 18:15 - loss: 0.2951 - accuracy: 0.9019
 44/163 [=======>......................] - ETA: 18:04 - loss: 0.2914 - accuracy: 0.9027
 45/163 [=======>......................] - ETA: 17:49 - loss: 0.2902 - accuracy: 0.9042
 46/163 [=======>......................] - ETA: 17:39 - loss: 0.2874 - accuracy: 0.9056
 47/163 [=======>......................] - ETA: 17:32 - loss: 0.2841 - accuracy: 0.9069
 48/163 [=======>......................] - ETA: 17:23 - loss: 0.2794 - accuracy: 0.9089
 49/163 [========>.....................] - ETA: 17:10 - loss: 0.2763 - accuracy: 0.9094
 50/163 [========>.....................] - ETA: 16:58 - loss: 0.2754 - accuracy: 0.9094
 51/163 [========>.....................] - ETA: 16:47 - loss: 0.2746 - accuracy: 0.9093
 52/163 [========>.....................] - ETA: 16:33 - loss: 0.2709 - accuracy: 0.9105
 53/163 [========>.....................] - ETA: 16:23 - loss: 0.2673 - accuracy: 0.9116
 54/163 [========>.....................] - ETA: 16:15 - loss: 0.2641 - accuracy: 0.9126
 55/163 [=========>....................] - ETA: 16:08 - loss: 0.2607 - accuracy: 0.9136
 56/163 [=========>....................] - ETA: 16:01 - loss: 0.2608 - accuracy: 0.9141
 57/163 [=========>....................] - ETA: 15:50 - loss: 0.2573 - accuracy: 0.9156
 58/163 [=========>....................] - ETA: 15:39 - loss: 0.2547 - accuracy: 0.9165
 59/163 [=========>....................] - ETA: 15:26 - loss: 0.2532 - accuracy: 0.9163
 60/163 [==========>...................] - ETA: 15:15 - loss: 0.2509 - accuracy: 0.9167
 61/163 [==========>...................] - ETA: 15:03 - loss: 0.2483 - accuracy: 0.9175
 62/163 [==========>...................] - ETA: 14:51 - loss: 0.2470 - accuracy: 0.9168
 63/163 [==========>...................] - ETA: 14:40 - loss: 0.2439 - accuracy: 0.9182
 64/163 [==========>...................] - ETA: 14:29 - loss: 0.2409 - accuracy: 0.9189
 65/163 [==========>...................] - ETA: 14:19 - loss: 0.2379 - accuracy: 0.9197
 66/163 [===========>..................] - ETA: 14:08 - loss: 0.2372 - accuracy: 0.9200
 67/163 [===========>..................] - ETA: 14:01 - loss: 0.2342 - accuracy: 0.9212
 68/163 [===========>..................] - ETA: 13:50 - loss: 0.2314 - accuracy: 0.9223
 69/163 [===========>..................] - ETA: 13:39 - loss: 0.2288 - accuracy: 0.9230
 70/163 [===========>..................] - ETA: 13:28 - loss: 0.2258 - accuracy: 0.9241
 71/163 [============>.................] - ETA: 13:17 - loss: 0.2255 - accuracy: 0.9239
 72/163 [============>.................] - ETA: 13:07 - loss: 0.2235 - accuracy: 0.9245
 73/163 [============>.................] - ETA: 12:56 - loss: 0.2213 - accuracy: 0.9251
 74/163 [============>.................] - ETA: 12:46 - loss: 0.2205 - accuracy: 0.9248
