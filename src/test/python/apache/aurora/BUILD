#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

python_test_suite(
  name = 'all',
  dependencies = [
    'src/test/python/apache/aurora/admin:all',
    'src/test/python/apache/aurora/client:all',
    'src/test/python/apache/aurora/common:all',
    'src/test/python/apache/aurora/config:all',
    'src/test/python/apache/aurora/executor:all',
  ]
)

python_library(
  name = 'api_util',
  sources = [ 'api_util.py' ],
  dependencies = [
    'api/src/main/thrift/org/apache/aurora/gen:py-thrift',
    'src/main/python/apache/aurora/client/api:scheduler_client',
  ]
)
