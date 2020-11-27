# Discount-Calculator-App
React Native App

import { StatusBar } from 'expo-status-bar';
import React, { Component } from 'react';
import { StyleSheet, Text, View, TextInput, Dimensions, Image } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text> Hassan Afzal (FA17-BCS-031)</Text>
      <Text> Shop Discount Calculator :</Text>
      <Text> Original Price :</Text>
      <TextInput
        keyboardType='numeric'
        style={styles.input}
        placeholder='Original Price in RS/.' />
      <Text> Discount Price :</Text>
      <TextInput
        keyboardType='numeric'
        style={styles.input} placeholder='Discount Price in RS/.' />
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: 'orange',
    alignItems: 'center',
    justifyContent: 'center',

  },
  input: {
    borderWidth: 1,
    borderColor: "#777",
    width: 200,
    margin: 8,
    padding: 6,
  }

});
