Build failed.  The message is a bit mixed--not clear if it is because of an actual disk quota or just the xcode signing (which I signed years ago, but apple never ceases to make you do more work).

  Unpacked download as cmdstan-2.26.1
      Building version cmdstan-2.26.1, may take several minutes, depending on your system.
      cmd: make build -j10
      cwd: None
      22:58:28 - cmdstanpy - WARNING - CmdStan installation failed.
      Command "make build" failed
      Command ['make', 'build', '-j10']
          error during processing Disc quota exceeded
      CmdStan installation failed.
      Command "make build" failed
      Command ['make', 'build', '-j10']
          error during processing Disc quota exceeded
      You have not agreed to the Xcode license agreements. Please run 'sudo xcodebuild -license' from within a Terminal window to review and agree to the Xcode and Apple SDKs license.



This could also be the 'prophet' warning the book gives in the opening chapter--I will have to look into that.
