# wcclj

A Clojure library designed to generate Hadoop application to count words based on [original WordCount example written in Java](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html#Example:_WordCount_v1.0).

## Compile

Compile it with `lein uberjar`. Application jar is at `./target/gd-0.1-standalone.jar`. The output file name might vary based on the version of the project. You can simply follow the output of the compilation process to aim the final UberJar file.

## Clean

Compile the project clean with `leain clean`.

## Usage

Use the output UberJar from the source on your Hadoop environment with ease.

## License

Copyright © 2022 FIXME

This program and the accompanying materials are made available under the
terms of the Eclipse Public License 2.0 which is available at
http://www.eclipse.org/legal/epl-2.0.

This Source Code may also be made available under the following Secondary
Licenses when the conditions for such availability set forth in the Eclipse
Public License, v. 2.0 are satisfied: GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or (at your
option) any later version, with the GNU Classpath Exception which is available
at https://www.gnu.org/software/classpath/license.html.
