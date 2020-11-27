# Discount-Calculator-App
React Native App

import { StatusBar } from 'expo-status-bar';
import React, { Component } from 'react';
import { StyleSheet, Text, View, Dimensions, Image, Button } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text> Hassan Afzal (FA17-BCS-031)</Text>
      <Text> Shop Discount Calculator :</Text>
      <Text> Original Price :</Text>
      <Text> Discount Price :</Text>
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
});

