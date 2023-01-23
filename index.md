# Test server for AlignSTS
<!-- AlignSTS: Speech-to-Singing Conversion via Cross-Modal Alignment -->

<!-- ## Abstract

The speech-to-singing (STS) voice conversion task aims to generate singing samples corresponding to speech recordings while facing a major challenge: the alignment between the target (singing) pitch contour and the source (speech) content is difficult to learn in a text-free situation. This paper proposes AlignSTS, an STS model based on explicit cross-modal alignment, we 1) adopt a novel rhythm adaptor to predict the target rhythm representation to bridge the modality gap between content and pitch, where the rhythm representation is disentangled in a simple yet effective way and is quantized into a discrete space; and 2) leverage the cross-modal aligner to re-align the content features explicitly according to the predicted rhythm and conduct a cross-modal fusion for re-synthesis. Experimental results show that AlignSTS achieves superior performance in terms of both objective and subjective metrics.  -->

## Singing Audio Samples
Note that the singer in the testing data could **not** be found in the training data.

### English
1. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/1.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/1.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/1.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/1.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/1.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
2. I can see the first leaf falling
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/2.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/2.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/2.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/2.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/2.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
3. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/3.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/3.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/3.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/3.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/3.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
4. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/4.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/4.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/4.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/4.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/4.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
5. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/5.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/5.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/5.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/5.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/5.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
6. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/6.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/6.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/6.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/6.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/6.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
7. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/7.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/7.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/7.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/7.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/7.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
8. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/8.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/8.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/8.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/8.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/8.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
9. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/9.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/9.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/9.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/9.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/9.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
10. But I do do feel that
    <table style='width: 100%;'>
        <thead>
        <tr>
            <th></th>
            <th>GT</th>
            <th>GT(HiFiGAN)</th>
            <th>Speech</th>
            <th>SpeechSplit 2.0</th>
            <th>AlignSTS</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <th scope="row">wav</th>
            <td><audio controls="" ><source       src="resources/audio/gt/10.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source      src="resources/audio/voc/10.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source       src="resources/audio/sp/10.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source    src="resources/audio/spsp2/10.wav" type="audio/wav"></audio></td>
            <td><audio controls="" ><source src="resources/audio/alignsts/10.wav" type="audio/wav"></audio></td>
        </tr>
    </tbody>
    </table>
