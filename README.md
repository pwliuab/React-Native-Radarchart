# React-Native-Radarchart

| Parameter | Type | Description |
| :--- | :--- | :--- |
| `dataList` | `obj` | **Required**. Your data shown on the radar chart.The key is the label and the value is the numerical result data.|
| `backGroundColor` | `string` | default "#91d9d4". The background color of the radar chart.|
| `radarSize` | `number` | default "1.2". The size of the whole chart. |
| `resultColor` | `string` | default "purple". The color of the result radar.|

## Example Usage

```
import RadarChart from 'react-native-radarchart';


function App() {
  return (
    <SafeAreaView>
      <RadarChart dataList={{能力: 1, 腦力: 3, 團隊: 4, 技能: 4.5, 積極: 3}} backGroundColor="#91d9d4" radarSize={1.1}  resultColor='purple'/>
    </SafeAreaView>
  );
}
 ```

![image](https://user-images.githubusercontent.com/67176560/183597822-46faab49-5b60-43ef-bd85-a892cbd2b318.png)
