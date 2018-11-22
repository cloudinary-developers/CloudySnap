# Testing Your App

`ClCamera` is now ready for use. Update your `App.js` file to render the component, as follows:

```text
    // src/App.js

    // other imports
    [...]
    import ClCamera from "./components/ClCamera";

    class App extends Component {

      // other component methods
      [...]
      render() {
        return (
          <div className="App">
            <Notifier offline={this.state.offline} />
            <header className="App-header">
              <img src={logo} className="App-logo" alt="Cloudinary Logo" />
              <h1 className="App-title">CloudyCam</h1>
            </header>
            <ClCamera offline={this.state.offline} />
          </div>
        );
      }
    }

    export default App;
```

Next, ensure that your development server is running on `http://localhost:3000`. Navigate to that URL on your browser and verify that the various versions of your app are displayed:

![App Demo \(Offline Mode\) \(1\)](../.gitbook/assets/ad-1.png)

![App Demo \(Online Mode\) \(2\)](../.gitbook/assets/ad-2.png)

![App Demo \(Offline Mode\) \(1\)](../.gitbook/assets/ad-3.png)

![Application Demo \(Offline Mode\) \(2\)](../.gitbook/assets/ad-4.png)

![App Demo \(Offline Mode\) \(3\)](../.gitbook/assets/ad-5.png)

