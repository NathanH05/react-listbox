# react-listbox
a double listbox react component

[![travis build](https://img.shields.io/travis/Sridatta19/react-listbox.svg?maxAge=2592000?style=flat-square)](https://travis-ci.org/Sridatta19/react-listbox)
[![VersionEye](https://img.shields.io/versioneye/d/Sridatta19/react-listbox.svg?maxAge=2592000?style=flat-square)]()
[![license](https://img.shields.io/github/license/Sridatta19/react-listbox.svg?maxAge=2592000?style=flat-square)]()

### Installation

This package can be installed via npm

```javascript
npm install react-listbox
```

![screen shot 2016-10-05 at 11 10 36 pm](https://cloud.githubusercontent.com/assets/11784027/19124722/edaa7f78-8b51-11e6-9723-2bb59aa35201.png)

### Usage

```javascript
import ListBox from 'react-listbox'
const options = [
  {label:'One', value: 1},
  {label:'Two', value: 2},
  {label:'Three', value: 3}
]
onChange = (selectedValues) => {
  // handle selected values here
}
<ListBox options={options} onChange={onChange}/>
```

### Other

This library was inspired by jQuery [multi-select](https://github.com/lou/multi-select/).
