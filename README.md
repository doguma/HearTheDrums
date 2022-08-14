# HearTheDrums
### "Extracting Drum Sounds with Magenta's GrooVAE"

**Train & Test Dataset** : [Groove MIDI Dataset](https://magenta.tensorflow.org/datasets/groove)
 -  *Jon Gillick, Adam Roberts, Jesse Engel, Douglas Eck, and David Bamman. "Learning to Groove with Inverse Sequence Transformations." International Conference on Machine Learning (ICML), 2019.*


**Model & Code Reference** : Magenta's [MusicVAE.ipynb](https://colab.research.google.com/github/magenta/magenta-demos/blob/master/colab-notebooks/MusicVAE.ipynb)

- Google Colab Hardware Setting : TPU
- Tensorflow Version : 2.9.1

**Contents**
- **Code** : Test_Project_Extracting_drums_from_MIDI_files.ipynb
- **Test Input File** :  input-rock-beat-midi.mid  (3_rock_105_beat_4-4.mid)
- **Test Output File** 
   - Generated samples (.mid) : output-hikl, output-lokl, output-nade-full, output-nade-reduced
   - Generated interpolation sample (.mid)
      - drums_2bar_nade_full, beat 3-4, temp 0.5, num_steps 13 (.mid) :  output-interpolated

---

**논문 & 코드 요약**
- **Paper Title** : "A Hierarchical Latent Vector Model for Learning Long-Term Structure in Music"
- **Notes** : https://www.notion.so/Extracting-Drum-Sounds-with-Magenta-s-GrooVAE-d5f93cba0f3843009ec6ea39fde0e4a6
