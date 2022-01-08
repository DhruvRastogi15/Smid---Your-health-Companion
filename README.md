# Smid---Your-health-Companion
Fitness tracking app

Functional Component Template 
-----------------------------------------------------------------------------------------------------------------------

import React, { useEffect } from "react";
import {View,Text} from 'react-native'

interface Props {
  navigation: any;
}

const ScreenName = (props: Props) => {

    const someFunction = async () => {

    }
    
    const someOtherFunction = async () => {
      
    }

    useEffect(()=>{
      const initializing = async () => {


        }
      initializing();
    },[])
    return (
      <View style={{ flex: 1, alignItems: 'center', justifyContent: 'center' }}>
        <Text>Screen Name</Text>
      </View>
    );
  }

export default ScreenName;

------------------------------------------------------------------------------------------------------------
